# Electronic-Engineer-Final-Project


The present project aims to develop a Hardware-in-the-Loop (HIL) system for the implementation
of an automatic control system within a simulated space environment. To
achieve this, a logical system architecture is defined to represent the different hardware and
software components of the HIL system, with the objective of establishing communication
between the elements and defining the system’s operational sequence. By establishing this
architecture, real-time communication is achieved with a sampling frequency of 500 Hz
and a maximum error of 6% between the sent and received signals.
A simulation environment is designed to integrate models that describe the space environment,
along with the implementation of a linear LQR controller to maintain the CubeSat’s
attitude at a desired position. Simulation results show that the attitude control is capable
of maintaining stability with an error of less than 2 degrees.
Additionally, as part of the validation of the developed system, the LQR controller was
implemented on the 3DOF Gyroscope plant using test cases for pointing the CubeSat to
Nadir, the Sun, and Zenith. During the tests, stable control was achieved on the plant,
with errors of less than 2 degrees on the pitch and yaw axes and 6 degrees on the roll
axis.
Finally, the system is evaluated by comparing the PD and LQR controllers. The conclusion
was that the LQR controller provides a better response when handling fixed references,
while the PD controller has superior adaptability to rapid changes in variable references
due to its derivative component in response to the actual error rate. It can be concluded
that the developed system is capable of assessing the performance of controllers in various
realistic CubeSat scenarios.
