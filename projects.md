---
layout: page
title: Projects
permalink: /projects/
---

These are some interesting projects I've worked on. They seem spread all over the place because I've worked on a bunch of different things, but it's been fun, and I have a pretty good idea where I'm headed now.

## Efficient Exploration with Ensembles of Value Estimates

### Guide: [Dr. Balaraman Ravindran, IIT Madras](http://www.cse.iitm.ac.in/~ravi/)

This is my favorite project so far. We'd had a pretty smart idea about exploration in RL with ensembles of value functions. The idea was to switch between multiple estimates of the value function for both behaviour and learning. The behaviour policy would always be greedy for the sampled value function estimate. The cool thing is that adequate exploration can be ensured by the differences between the different estimates. It worked very well on quite a few RL problems. We were about to submit a paper to a workshop as well, when we found that Bootstrapped DQN, published a couple of months earlier, was essentially the same idea and had already been tested on much harder problems than we had considered. In any case, [here](https://drive.google.com/file/d/0B9JFuMiqGShfOHVqMkdqUlJ2bGM/view?usp=sharing) is a preliminary write-up of our work.

<br>

## Inverse Modeling of the Muscle Spindle

### Guide: [Dr. Francisco Valero-Cuevas, USC](http://bbdl.usc.edu/Francisco.php)

Muscle spindles are sensory receptors that convey the length and velocity information of the muscle in which they are embedded (proprioception) to the central nervous system (CNS) via sensory neurons. The sensitivity of the spindle is itself modulated by the CNS through the gamma motoneurons (fusimotor system). While it has been possible to record from the output of the spindle, there is no available technique to record the fusimotor drive.

In light of this, I spent my summer internship at the [Brain Body Dynamics Lab](http://valerolab.org/about/), building an inverse model to infer the trajectory of the fusimotor drive using the output record, spindle firing rate, and its length and velocity. The inverse model is meant to be used in experiments with a neuromorphic robotic arm. That sounds pretty cool because it actually is.

<br>

## A Reinforcement Learning Agent to play the 2048 Puzzle Game

<br>
## A Spectrum Analyzer built from Basic Analog Circuitry
