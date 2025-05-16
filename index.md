## Animation
The animation below shows the evolution of isochoric Λ<sub>c</sub> in a 1D coronal loop simulation published in this [submitted paper](https://arxiv.org/abs/2408.15869).  Each simulation is initialized with an approximate static equilibrium solution under uniform heating, which relaxes to a proper equilibrium before a spatially dependent, exponential heating term is gradually introduced at t = 10⁵ s (note the time in the animation denotes the time in hours after heating is implemented).  The first frame begins from a state where the loop has stabilized into a repeating thermal nonequilibrium (TNE) cycle.  The first time step is at peak temperature during one TNE cycle, about 11.8 hours (13 thermal times) after exponential heating was fully implemented in the simulation.  Here, Loop 2 appears thermally stable. However, over the next few hours, the cooling rate, Λ(T) (black line), increases and eventually surpasses the critical cooling rate, isochoric Λ<sub>c</sub> (blue line).  The red highlighted portions of the black lines indicate where Λ(T) > Λ<sub>c</sub>, indicating instability.  Around 3.6 hours later, a dense, cool condensation forms within the loop. This event aligns with theoretical expectations: based on the isochoric growth rate, the timescale for instability is approximately 6.6 hours. Thus, our analysis points to the cause of condensations in TNE loops being the exponential growth of CC modes.

<video poster="fig8.png" width="675" height="270" controls preload> 
    <source src="tne_CC_mode.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="tne_CC_mode.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### Acknowledgements
These simulations were run using the ARGOS code and were provided by James Klimchuk and Manuel Luna.  Though not published, this run was part of the study for their [paper](https://ui.adsabs.harvard.edu/abs/2019ApJ...884...68K/abstract).
