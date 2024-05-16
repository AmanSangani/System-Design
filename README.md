# System-Design
Learning System Design


# Lift System Design

## Overview

This document provides an overview of the design of a lift system, detailing the object-oriented approach, algorithms for elevator operation, use cases, and limitations.

### Algorithm for Elevator Operation

The lift system here explained employs a "closest first" algorithm for elevator operation. This algorithm prioritizes picking up passengers closest to the current floor of the elevator. An optimization to this algorithm ensures that when the elevator is moving in a particular direction, it prioritizes picking up passengers traveling in the same direction.

### Limitations

A limitation of the closest first algorithm is discussed: passengers on the highest floor of the building may experience indefinite wait times for the elevator to descend and pick them up.

## Contributors

- [Aman Sangani]

![Elevator System](elevator_system.png)

