# How-many-Dissenters-Does-it-take-to-Disorder-a-flock-An-active-matter-Project
## BACKGROUND

This project is based [this](https://drive.google.com/file/d/11l1hnhAybBlAGpikmnDgNc--NeyH7tZ1/view?usp=sharing)
 Research paper under the supervision of Professor Pintu Patra , IIT Kharagpur in Active Matter Course.
Flocking Models: Vicsek-inspired models describe how active agents (e.g., birds, bacteria) tend to align their movement with neighbours, creating collective motion, and transitioning from disorder to an aligned flock state based on noise or density.


Dissenters vs. Aligners: The paper studies how a small number of "dissenters" (non-aligning agents) disrupt a well-ordered flock, even when agents only repel (no attractive forces).	

Impact of Dissenters: A tiny fraction of dissenters (pc = 0.004) can break the flocking order, while static obstacles only cause local disturbances without fully disrupting alignment.

Hydrodynamic Model: The study uses a hydrodynamic model to show that motile dissenters cause a more significant disordering effect, due to their persistent movement, compared to static obstacles.

Practical Implications: These findings suggest that motile dissenters could be useful for crowd control, as they rapidly disrupt collective behavior in groups like human crowds

## MODEL & SIMULATIONS
 
Model Overview: The system consists of active Brownian particles (ABPs) in a 2D box with periodic boundary conditions. Each particle has a position and an angle defining its direction of movement.

Equations of Motion: Particle movement follows Langevin equations, where self-propulsion is along a specific direction, and repulsive interactions prevent overlap. Noise affects the rotational motion, causing small fluctuations.

Flocking Transition: The system transitions from a disordered state to a flocking state (aligned movement) when noise is low or particle density is high.

Simulation Setup: In simulations, particles have a set radius and propulsion speed, with packing fractions varied to observe flocking behaviour. Systems include up to 20,000 particles.

Dissenters: A fraction of particles (dissenters) do not align with others, and their impact on flocking is studied at different densities and proportions.

## KEY PARAMETRS

Packing Fraction(φ): The density of particles in the system.
Noise (η): Controls how much randomness is added to the direction of motion.
Fraction of Dissenters (ρ): The percentage of particles that do not follow the alignment rule.
System Size(L): Simulations are run for different sizes to observe how results scale with the number of particles.







