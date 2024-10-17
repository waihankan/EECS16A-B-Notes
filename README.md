# EECS16A and EECS16B Notes
My brief notes from EECS16A and EECS16B



## EECS16A
### Course Information [From Course Website]
The EECS 16AB series (Designing Information Devices and Systems) is a pair of introductory-level courses introducing students to EECS. The courses have a particular emphasis on how to build and understand systems interacting with the world from an informational point of view. Mathematical modeling is an important theme throughout these courses, and students will learn many conceptual tools along the way. These concepts are rooted in specific application domains. Students should understand why they are learning something.

An important part of being a successful engineer is being able to identify the important and relevant structure in a complex problem while ignoring minor issues. EECS 16A focuses on modeling as abstraction: how can we see the relevant underlying structure in a problem? It introduces the basics of linear modeling, largely from a "static" and deterministic point of view. EECS 16B deepens the understanding of linear modeling and introduces dynamics and control, along with additional applications. Finally, CS 70, (which can be thought of as the third course in this sequence --- except without any labs), introduces additional discrete structures for modeling problems, and brings in probability.

In EECS 16A in particular, we will use the application domains of imaging and tomography, smartphones and touchscreens, and GPS and localization to motivate and inspire. Along the way, we will learn the basics of linear algebra and, more importantly, the linear-algebraic way of looking at the world. The emphasis will be on modeling and using linear structures to solve problems; the class is not just focused on how to do computations. We will learn about linear circuits, not merely as a powerful and creative way to help connect the physical world to what we can process computationally, but also as an exemplar of linearity and as a vehicle for learning how to do design. Circuits also provide a concrete setting in which to learn the key concept of "equivalence" --- an important aspect of abstraction. Our hope is that the concepts you learn in EECS 16A will help you as you tackle more advanced courses and will help form a solid conceptual framework that will help you learn throughout your career.

### Covered Topics
#### Linear Algebra
- [ ] Introduction to Imaging
- [ ] Tomography and Linear Equations
- [ ] Gaussian Elimination
- [ ] Span, linear independence and dependence
- [ ] Linear Transformations, Matrix multiplication
- [ ] Inversion
- [ ] Vector Spaces: Null spaces and Columnspaces
- [ ] Page Rank, Eigenvalues and Eigenspaces

#### EE Basics
- [ ] Node Voltage Analysis, Voltage Divider
- [ ] 1D Touchscreen, Power and Voltage/Current Measurement
- [ ] 2D Resistive Touchscreens
- [ ] Superposition and Equivalence
- [ ] Capacitors
- [ ] Capacitors and Capacitive Touchscreen
- [ ] Capacitive Touchscreen and Capacitance Modeling

#### Operational amplifier
- [ ] Op-amps and Negative Feedback
- [ ] Op-amp circuit analysis
- [ ] Circuit Design Examples

#### Vector Projection, Correlation, etc.
- [ ] Introduction to GPS
- [ ] Correlation and Classification
- [ ] Least Squares Algorithm


---

## EECS16B
### Course Information [From Course Website]
The goal of the EECS 16 series is to introduce students to the various topics in the broad world of EECS while strengthening core mathematical principles to analyze linear systems as engineers. The EECS 16 series labs aim to provide students with real, hands-on applications of the concepts they learn in lecture and develop design-thinking skills.

EECS 16B will first walk students through more advanced circuitry; this first module of the class introduces students to the frequency domain, a tool critical in circuitry and analyzing many real-world systems. In the next module, students will understand stability and controllability of systems, pertinent concepts for robotics. In the final module, students will develop fundamental linear algebra building blocks, like SVD, to set them up to implement classification via PCA, a prominent algorithm in machine learning.

Simultaneously, in lab sections, students will apply these theoretical concepts to a real-world project: S1XT33N, a voice-controlled car. S1XT33N implements all the key system components students learn in lecture: analog sensor interface, control, and classification of collected data. Labs enable a deeper conceptual understanding of the course material, while improving students' physical intuition and confidence with problem-solving skills: critical thinking, design thinking, and tenacity via debugging.

EECS 16B is a followup course to EECS 16A and can be considered a precursor to many upper division EECS courses. Below is an example of a high level system consisting of these upper division courses that the EECS 16 series is an essential precursor to.

### Covered Topics
#### Capacitors, RC, RLC, CMOS
- [ ] Capacitors, RC Circuits, 1st Order Differential Equations
- [ ] Inductors, RL Circuits, etc
- [ ] CMOS Transistors and Transistor RC Model / DACs, ADCs
- [ ] RLC Circuits, 2nd Order Differential Equations
- [ ] Impedances, Frequency Domain Theory, Complex Exponentials

#### Signals and Systems
- [ ] Transfer Functions
- [ ] Bode Plots, Poles and Zeros
- [ ] Signals & Systems, State Space, and Vector Differential Equations
- [ ] Natural Response: Solving ẋ = Ax
- [ ] Forced Response: Solving ẋ = Ax + Bu
- [ ] Signals and Systems in Discrete Time; Hybrid Systems
- [ ] System ID
- [ ] System Stability and Feedback Control (BIBO and Internal Stability)
- [ ] Controllability

#### Linear Algebra
- [ ] Gram Schmidt
- [ ] Spectral Theorem and Min. Energy Control
- [ ] SVD
- [ ] SVD Applications
- [ ] PCA
- [ ] PCA Applications
- [ ] Linearization
- [ ] Special Topics (MRI by Prof. Lustig
