---
title: "Implementing Dynamic Active Constraints for Safe Remote Robotic Surgery in SOFA"
collection: talks
type: "SOFAWeek2020"
permalink: /talks/sofa-week-1
date: 2020-10-20
---

<div style='text-align: justify;'>
Safe navigation of body lumens and interaction with organs is an open challenge in Minimally Invasive Surgery (MIS). Simulating active constraints on soft-tissue for surgical robots has been a promising solution to this challenge; with active constraints, the robot is guided to move in a safe imaginary passage during a MIS navigation or interaction task. This research presents a way to utilize SOFA (Simulation Open Framework Architecture) to implement dynamic active constraints for safe remote robotic palpation and navigation around an organ through a Geomatic Touch haptic interface with force feedback. An active constraint is formulated as a Bilateral Constraint, using the SOFA Sliding Constraint module, between two safely interacting objects, here the robot tip and liver tissue. By simulating a path-following navigation scenario with and without the active constraints in SOFA, we observed a significant improvement (13.034 mm vs 0.009 mm) in the path following error in the presence of active constraints. These results can be used to simulate more complex surgical scenarios in SOFA as well as for semi-autonomous navigation of surgical robots in real life.
</div>


