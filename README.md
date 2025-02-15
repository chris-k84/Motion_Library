# Motion Library

## Contents

1. [Motivation](#motivation)
2. [The Goal](#the-goal)
3. [Background](#background)
4. [Description](#description)
3. [Repository Design](#repository-design)
4. [Tests](#Tests)
5. [Support](#Support)
6. [Requirements](#Requirements)
7. [Documents](#Document-List)

## Motivation

This started out as an XTS library, then became something else, a huge crawling repo with too much stuff doing too many things. So it's been broken up into numerous libraries which will break out the elements into modules which align in function and intent. Basically the motivation is to have a clue whats going on :-) 

## The Goal

The goal of this repo is to build on the base repo, using the cyclic modules to create an object specifically to run an axis. The library combines the objects from the base library and the blocks from the MC2 library. 

## Background



## Description

The repo contains a number of classes that provide execution of the baseic functions of the MC2 library. A class to contain the behaviour of MC_Power, MC_Reset, MC_Halt and MC_MoveAbsolute are packaged into the MC2_Axis_Base class. This can be instantiated and used to control an axis via the TwinCAT NC.

## Repository Design

This repo is split into 2 projects, the library containing the motion classes and a unit tesitng library.
Utilising reference libraries you can run them, you can run in UmRT.


## Tests

Tests are implemented in a Test Project, the library is referenced there and tests are run in a TwinCAT RT or UmRT.

## Support

LOL, little old me now, all by myself :-)


## Requirements: 

Please include important requirements in the local readme files.

Currently nothing more than:

TwinCAT 4026


## Document List





