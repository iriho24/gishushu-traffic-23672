Traffic Light System for Gishushu, Kigali - Specification
This project implements a traffic light system for the Gishushu intersection in Kigali, following the state diagram shown in the design. The traffic lights alternate between two main traffic flows and a pedestrian crossing phase, with each phase carefully timed to ensure smooth traffic flow and pedestrian safety.

Traffic Flow Overview
1.Remera-Convention Center Green, Nyarutarama-KG6 Avenue Red

The traffic light allows vehicles from the Remera-Convention Center direction to move through the intersection.
The Nyarutarama-KG6 Avenue direction is red, stopping vehicles from crossing.
Duration: 60 seconds.
2.Remera-Convention Center Yellow, Nyarutarama-KG6 Avenue Red

The traffic light for Remera-Convention Center direction changes to yellow as a warning to prepare vehicles to stop.
The Nyarutarama-KG6 Avenue direction remains red.
Duration: 3 seconds.
3.Nyarutarama-KG6 Avenue Green, Remera-Convention Center Red

The traffic light allows vehicles from the Nyarutarama-KG6 Avenue direction to proceed.
The Remera-Convention Center direction is red, stopping vehicles from crossing.
Duration: 60 seconds.
4.Nyarutarama-KG6 Avenue Yellow, Remera-Convention Center Red

The traffic light for the Nyarutarama-KG6 Avenue direction changes to yellow as a warning to prepare vehicles to stop.
The Remera-Convention Center direction remains red.
Duration: 3 seconds.
5.Both Directions Red (Pedestrian Cross-Walking)

After both directions turn red, the pedestrian cross-walk phase activates, allowing pedestrians to safely cross the intersection.
Duration: 30 seconds.
6.Return to Initial State

After the pedestrian phase, the cycle restarts from the first state, allowing vehicles from the Remera-Convention Center direction to proceed.
Implementation Notes
This cycle ensures efficient traffic flow and pedestrian safety by prioritizing each direction in sequence.
Each state change is timed to optimize traffic movement and minimize waiting times.
