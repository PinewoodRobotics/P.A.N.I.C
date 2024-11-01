# P.A.N.I.C

Pi AI Node In Charge

---

## Function

The function of P.A.N.I.C is to be the central unit of processing of the image recognition data coming in from many other nodes on the robot.

## Description

This is primarally made in order to have all the code for similar things in one place rather than scattered over many repositories. However, this mostly contains many standalone code bases that run as different processes and can be made into separate libraries in the future.

## Contains

1. communication
   1. between processes
   2. between nodes
2. recognition modules
   1. april tag recognition and distance estimation [to it]
   2. robot image recognition and distance estimation [to it]

## Documentation

The documentation of each "module" can be found in the corresponding folders where the root of the corresponding module is.

### Read Me

1. [Communication](communication/README.md)

## Goal

The main goal of this is to create a code base such that we can put it on a raspberry pi, run one command, and everything is up and running.