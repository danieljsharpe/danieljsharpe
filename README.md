# Markov chain analysis and simulation with DISCOTRESS

<!-- <a href="#">DISCOTRESS</a> -->
<!-- ![Getting from B to A in a Markov chain](discotress_network_annotated.png) -->

<!-- <img_src = "https://raw.githubusercontent.com/danieljsharpe/danieljsharpe/master/discotress_network_annotated.png" alt="Markov chain"> -->

<!-- ![Getting from B to A in a Markov chain](https://github.com/danieljsharpe/danieljsharpe/blob/master/discotress_network_annotated.png?raw=true) -->

<p align="center">
  <img src="https://github.com/danieljsharpe/danieljsharpe/blob/master/discotress_network_annotated.png">
  <i>A finite Markov chain is a discrete-state stochastic model where edges connecting nodes of the network are associated with transition probabilities for a fixed time step (discrete-time Markov chain) or transition rates (continuous-time Markov chain). Often, we want to analyse the characteristic features of transitions from an initial set of nodes, &#120069;, to a target set of nodes, &#120068;. Dynamical properties of interest include the occupation probabilities of nodes at equilibrium (illustrated by the sizes of nodes in the above image), the probabilities that nodes are visited along &#120068; &#8592; &#120069; trajectories (indicated by node opacity), and the net productive &#120068; &#8592; &#120069; flux along edges (indicated by edge thickness). These quantities, and many others, can be determined using the <a href="https://github.com/danieljsharpe/DISCOTRESS">DISCOTRESS</a> software package, either through exact computation by numerically robust algorithms, or estimated from simulation data obtained using efficient path sampling methods.</i><br>
</p>

Finite Markov chains are network models commonly used to represent stochastic processes as varied as animal movement within an ecosystem 🦜🌴, the fluctuating status of financial markets 💸📈, and biomolecules such as proteins or DNA folding to their functional structure 🧬🦠. [DISCOTRESS](https://github.com/danieljsharpe/DISCOTRESS) is a  powerful and flexible software package to analyse the dynamics of finite Markov chains. The Markov chain dynamics can be studied at both a global level, where the MFPT (mean first passage time; the average time to reach the target state &#120068; from an initial state &#120069;) is a key quantity, and in detail, by identifying the features of dominant &#120068; &#8592; &#120069; paths and quantifying the influence of local states for the transition between two endpoint states &#120068; and &#120069;.

[DISCOTRESS](https://github.com/danieljsharpe/DISCOTRESS) is specifically designed to treat Markov chains featuring a comparatively slow (i.e. low probability) event. This separation of timescales is a common feature of realistic dynamical models - for instance, in a population dynamics model of an ecosystem 🦜🏝️, births and deaths of individuals take place on a fast timescale compared to large-scale changes such as extinction of a species. In general, we are interested in studying a particular &#120068; &#8592; &#120069; process representing a significant change in system state that is rare compared to unproductive fluctuations. For Markov chains exhibiting rare event dynamics, standard algorithms to compute dynamical quantities are numerically unstable, and the simple kinetic Monte Carlo (kMC) method to simulate pathways is severely inefficient. DISCOTRESS includes a suite of advanced algorithms that negate these problems, including numerically robust state reduction algorithms to compute exact dynamical quantities, and efficient simulation algorithms to sample paths. Get started with the software [here](https://github.com/danieljsharpe/DISCOTRESS).

## About me

I am enthusiastic about creating and analysing computer models to investigate complex real-world problems, especially dynamical processes. I completed a PhD at the University of Cambridge, during which I began development of my DISCOTRESS program. Much of my work deals with the theory of Markov chains, but I am also interested in applications to the modeling of biophysical, ecological, and economic systems. More broadly, I have research interests that encompass stochastic modeling, optimization, network science, and machine learning.

I love wildlife and nature, and I like to spend my free time making visual artworks of critters 🦜🦌🦨🦩🦎🐫 and the landscapes 🏞️ they inhabit, especially the Southwest desert 🏜️ and prairie biomes of North America. I work with graphite and charcoal pencils as well as digital painting.

<!-- The capabilities of the software include exact computation of dynamical properties by numerically stable state reduction algorithms and sampling of pathways on the network by state-of-the-art simulation methods. -->

<!--
**danieljsharpe/danieljsharpe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
