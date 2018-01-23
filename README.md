# Kidnapped Vehicle Project

## Description
The robot has been kidnapped and transported to a new location. It has a map of this location, a (noisy) GPS estimate of its initial location, and lots of (noisy) sensor and control data.

In this project a 2 dimensional Monte Carlo Localisation filter (a particle filter) is implement in C++. At each time step the filter gets observation and control data.

## Building instructions

Execute from the top directory of the project:

* `./clean.sh`
* `./build.sh`
* `./run.sh`

