
# MM204 Programming Assignment

*Note-The methodology for solving the problem has been included in this Readme file*

The code aims to solve Problem Number 8 of the given programming assignment based on Transient heat conduction  

## Running the code

The code is in the form of a .m file which can be downloaded and run in an Octave or Matlab environment.

**Octave**

In the Editor tab click on Run > Save File and Run/Continue

**Matlab**

On the Editor or Live Editor tab, in the Section section, select Run and Advance

## Results

On running the code, the command window shows the output as:

Time required for the midlength of the rod to reach 100C is 311.000000 s

A graph is shown which gives the temperature profile with x coordinate for different times of 0s,200s,400s and 910s.


## Methodology

Assumptions Taken :

(a) One-dimensional transient conduction in the rod.

(b) Uniform h along the rod and at the end.

(c) Negligible radiation exchange between rod and surroundings.

(d) Constant Properties of Material.

First of all, Choosing Δx = 0.016 m, the finite-difference equations for the interior
and end nodes are obtained. Regrouping the equation, we obtain Ti
in terms of
Ti, Ti-1
, Ti+1
, Fo and Bi. For the first nodal point, Ti-1
is taken as To which is 200℃.
Here, By using the formula we have found the value of Fo & Bi.

## Authors

Group 31 Team members:

- Aditya Anil Wankhade 200110008
- Daniel Joel Gracias  200110029
- Sakshi Agarwal  20D110022
- Sarthak         20D110024
