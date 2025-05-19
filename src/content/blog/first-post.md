---
title: "Superconducting Frame in Magnetic Field"
description: "Electrodynamics"
pubDate: "Jul 08 2022"
heroImage: "/blog-placeholder-3.jpg"
---
<!-- Katex -->
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/katex@0.15.2/dist/katex.min.css"
  integrity="sha384-MlJdn/WNKDGXveldHDdyRP1R4CTHr3FeuDNfhsLPYrq2t0UBkUdK2jyTnXPEK1NQ"
  crossorigin="anonymous"
/>

A superconducting square rigid frame of mass $m$, inductance $L$, and side $a$ is cooled down (in a magnetic field) to a temperature below the critical temperature. The frame is kept horizontal (parallel to the $x-y$ plane) and constrained to move in the $z$ direction in a nonuniform but constant magnetic field described by a vector potential: </br></br>

$$\vec{A} = (-B_0 y, \alpha x z, 0)$$  </br>

and a uniform gravitational field given by the acceleration $g$. Let's assume that the thickness of the frame is much smaller than $a$. Let's also assume, for the ease of calculation, that it is initially at rest, with its center coinciding with the origin. 
<br><br>
$$\vec{B} = \vec{\nabla} \times \vec{A} = \begin{vmatrix} \hat{x}                         & \hat{y}                       & \hat{z}\\[6pt] \frac{\partial}{\partial x}     & \frac{\partial}{\partial y}   & \frac{\partial}{\partial z}\\[6pt] -B_0                            & \alpha x z                    & 0 \end{vmatrix} = (- \alpha x , 0, \alpha z + B_0 )$$
<br><br>
The magnetic flux $\Phi$ through the surface of the superconducting frame is constant. $\phi$ is composed of the flux from the external magnetic field $\Phi_e$ and the flux $\Phi_i$ produced by the current $I$ flowing in the frame:
<br><br>
$$\Phi = \Phi_e + \Phi_i = \vec{B} \cdot \vec{S} + \frac{1}{c} L I = (B_0 + \alpha z) a^2 + \frac{1}{c} L I $$
<br><br>
