# CI_CD_Setup
The goal of this repository is primarily to learn about modern technologies in the server/container/cloud sector.

## Critical questions
- Is it possible to create a platform independent hosting setup programmatically?
- Can the API development be simplified?
- Is a generalized way to create and communicate with containers dangerous?

## Goals
All goals are handled with minimal manual input in mind.
1. Creating a container and its contents automatically.
2. Configuring the way ( e.g. internet/local network ) a container can be accessed.
3. Communication between containers

## Special conditions
The performance aspect will be considered.
If a significant performance loss compared to monolith structures can be measured, then this project is a failure.

## Motivation
As stated above, this project is used to learn more about modern architectures and ways to structure data and functional code.
I want to learn about the current possibilities and limitations of containerized/minimal environment structures.

## Tools
FOS and highly customizable tools are prioritized.

## Research steps
1. What is "containerarization"?
  - is a type of virtualization [1] 
  - also called "OS-Virtualization" [1] 
  - potentially reduces overhead and improved utilization of datacenters [1] 
  - cpu, memory, network efficient [1]
  - not only OS, but also applications can be containerized
2. What are limitations?
  - Linux applications would need a linux host [1] -> conflicts with goal "platform independent" 
  - Mac is less supported [1] -> restricting os complications?
3. What types of "containers" are already existent?


## Sources used
[1] https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8861307
