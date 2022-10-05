# ROS Modelling Assignment

In this assignment you will model a robotic system and its interactions with the environment using the *JetBrains MPS*.

## Learning Objectives

The student should be able to

- understand the concepts of Model- and Domain-Specific languages
- know how to use the *JetBrains MPS* for modelling robotic systems

## Task

### Outline
We are continuing our well-known warehouse example from the previous assignments with some slight modifications. Namely,
the robots do **not get their exact position** from a central server, but can instead query **four beacons**, that are
positioned at the **four corners** of the rectangular warehouse, for their **relative distance** with respect to it.  
Additionally, every robot is equipped with a [laser rangefinder](https://en.wikipedia.org/wiki/Laser_rangefinder), that
can measure distances of up to four tiles. It performs measures in four directions, i.e. it can **not measure
diagonally**. Furthermore, the robots have a map of the environment, which can be updated by a central server.

### Instructions

- [ ] Make yourself familiar with the *JetBrains MPS* (see resources)
- [ ] Complete the tutorial and set up your MPS environment
- [ ] Model the well known warehouse example
- [ ] Provide a short write-up of your ideas and modeling decisions in the `writeup.md` file.
- [ ] Prepare yourself for a short (5min) in class presentation of your model

## Resources

- [MPS User's Guide](https://www.jetbrains.com/help/mps/mps-user-s-guide.html)
- 
