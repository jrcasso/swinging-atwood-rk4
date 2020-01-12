# RK4: Swinging Atwood's Machine

This is a simulation of the Swinging Atwood's Machine using a 4th-order Runge-Kutta algorithm.
The Swinging Atwood's Machine (SAM) is an extension of the prototypical Atwood's machine where one mass is permitted an additional degree of freedom to swing.
This particular system is an excellent example of how even simple systems can exhibit characteristics of chaos.

The following video is a sequential aggregation of several trajectories over incrementally varying intial conditions, and produces quite an interesting progression:

[![](http://img.youtube.com/vi/p-PyVs0FVVA/0.jpg)](http://www.youtube.com/watch?v=p-PyVs0FVVA "SAM")

The code in this repository generates images of various trajectories given a set of varying initial conditions:
Below are examples of non-chaotic and chaotic trajectories, respectively.

![order](https://imgur.com/Za8zSfD.png)

![chaos](https://imgur.com/uVOt0cz.png)

## System Dynamics

The dynamics of this system are most easily described using the generalized coordinate system established by the diagram below.
From the Euler-Lagrange equations, this system yields the following coupled, second-order, ordinary differential equations:

![Link](https://imgur.com/Y2qD4Lk.png)

## System Diagram
![Link](https://imgur.com/kcF5o9t.png)


