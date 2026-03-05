Project Overview

This project focuses on analyzing a power distribution network using nodal analysis and linear approximation techniques. The electrical network equations are formulated using Kirchhoff’s Current Law (KCL) and represented in matrix form. MATLAB is used to compute node voltages and branch currents efficiently.

The system of equations is expressed in matrix form:

[𝐴][𝑉]=[𝐵]
[A][V]=[B]

Where:

A = Coefficient Matrix
V = Node Voltage Matrix
B = Constant Matrix
By solving this equation using MATLAB, the unknown node voltages and branch currents in the electrical distribution network can be obtained efficiently. This approach simplifies the analysis of complex electrical systems using numerical methods. 
Objective

The objectives of this project are:
To analyze a small electrical distribution network using nodal analysis.
To represent the circuit equations in matrix form using linear algebra.
To solve the system of equations using the inverse matrix method in MATLAB.
To compute node voltages and branch currents using numerical techniques.

Problem Description

In electrical power distribution networks, it is necessary to determine node voltages and current flow in different branches. Analytical solutions become difficult for complex networks with multiple nodes.
The circuit considered in this project consists of:
Multiple resistors
Voltage sources
A current source
The bottom conductor of the circuit is considered as the reference node (ground). The objective is to determine the unknown node voltage and currents flowing through each branch of the network.
Using numerical methods and MATLAB computation greatly reduces manual calculation effort and improves accuracy.

Methodology

The following steps were followed in this project:
Identify all circuit components and their values.
Select the reference node (ground).
Apply Kirchhoff’s Current Law (KCL) at the unknown node.
Formulate the circuit equation in algebraic form.
Convert the equation into matrix representation.
Solve the matrix equation using MATLAB numerical computation.
Compute branch currents using Ohm’s law.
Verify the results using KCL validation.

Result

The MATLAB program produces the following results:
Node Voltages
VA = 23.71 V
VB = 12 V

Branch Currents
Branch	Current	Direction
R1	2.00 mA	Node B → Ground
R2	5.86 mA	Node A → Node B
R3	-4.86 mA	48V Node → Node A
Current Source	1 mA	Upward

The negative value of current in R3 indicates that the actual current direction is opposite to the assumed direction.

Engineering Significance

This project demonstrates the importance of numerical methods in electrical network analysis.
Key engineering benefits:
Efficient solution of complex circuits
Reduced manual computation errors
Easy scalability for large power systems
Verification of circuit laws using computational tools
Useful for power system load flow analysis
MATLAB provides a powerful platform for solving systems of equations and analyzing electrical networks efficiently.

How to Run the Project

Follow these steps to execute the project:
Install MATLAB on your system.
Create a new MATLAB script file.
Copy and paste the provided MATLAB code.
Save the file as:
power_distribution_load_flow.m
Run the script in MATLAB.
The program will display node voltages and branch currents in the command window.

Project Summary

This project analyzed a power distribution network using nodal analysis and MATLAB computation. The circuit equations were formulated using Kirchhoff’s Current Law and solved using the inverse matrix method.
The numerical solution successfully determined the unknown node voltage and branch currents, verifying the validity of circuit laws. The study demonstrates how computational tools like MATLAB simplify electrical network analysis and enable accurate solutions for engineering problems.
