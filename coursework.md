---
layout: page
title: Coursework
permalink: /academics/
---

These are some interesting projects I've worked on. They seem spread all over the place because I've worked on a bunch of different things, but it's been fun, and I have a pretty good idea where I'm headed now.

## Efficient Exploration with Ensembles of Value Functions

This is my favorite project of them all. We'd had a pretty smart idea about exploration with ensembles. The idea was to switch between multiple independent estimates of the value function for both behaviour and learning. The behaviour policy is always greedy with respect to the sampled estimate, while the differences between different estimates ensures adequate exploration. It worked surprisingly well on a lot of RL problems. We almost submitted this to a workshop too, but then we saw that Bootstrap DQN was essentially the same idea, and had already been tested on much harder problems.

## Inverse Modeling of the Muscle Spindle

Muscle spindles are sensory receptors that convey the length and velocity information of the muscle in which they are embedded (proprioception) to the central nervous system (CNS) via sensory neurons. The sensitivity of the spindle is itself modulated by the CNS through the gamma motoneurons (fusimotor system). While it has been possible to record from the output of the spindle, there is no available technique to record the fusimotor drive.
\\
In light of this, I spent my summer internship at the [Brain Body Dynamics Lab](http://valerolab.org/about/), building an inverse model to infer the trajectory of the fusimotor drive using the output record, spindle firing rate, and its length and velocity. The inverse model is meant to be used in experiments with a neuromorphic robotic arm. That sounds pretty cool because it actually is. 

## A Reinforcement Learning Agent to play the 2048 Puzzle Game

## A Spectrum Analyzer built from Basic Analog Circuitry
