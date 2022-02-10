### Simulation Methods
<!--- ### DFT Theory Overview
Solving the many electron wave function is so difficult due to the untenable degrees of freedom present in a many electron system. --->
- [[?]] Currently have a broad understanding of the approximations involved to solve the Schrodinger equation for multi-electron systems, but don't have a thorough enough math/physics background to know what assumptions are adequate to model chiral systems. 
- [[?]] There are some fundamental assumptions to these theoretical models that I do not fully understand. I don't fully understand the conduction mechanism of the electron through the chiral molecule. What is the band structure of typical proteins and dna? Or is the trajectory just traveling inside the cavity of the chiral molecule? I'm not entirely sure. 
- [[?]] Does tunneling immediately imply the collapse of the wave function? Would that mean that the mechanism of tunneling as electron transport immediately implies decoherence. (Though I'm aware decoherence doesn't immediately mean the collapse of the wave function.)
- [[?]] Found some older papers about experimental tunneling transport through molecular junction, but I'm not sure if this regime was the same regime measured in the CISS experiments. 
- [[?]] The linear momentum along helicla trajectory is described as essential to the description of the effect, but I'm not sure if this is consistent with experimental descriptions of coherent tunneling through molecular orbitals. 

What happens to electrons that go through with the wrong spin. 
- Since traditional DFT methods ignore spin, typically some semi-empirical approach with a Hamiltonian model is used to model the system. 
- Hamiltonian models usually are simplified to a single electron traveling along a helical path


### Semi-analytical solution from Zollner et. al. (2020)^[[![[@zollner_insight_2020#^74b905]]]]

This analysis provides a symmetry analysis of the electron transmission through a chiral moleule

Initial atomistic approaches use tight binding models with ad-hoc parameters defined for the Hamiltonian based on a semi-empirical methodology determined by Medina et. al  [[cite]].^[![[@zollner_insight_2020#^74b905]]]

[[@michaeli_origin_2019]]

[[Limitations of Ab Initio Methods]]
[[why perform simulations]]



#### 1-D description for spin-dependent effects (Geyer et al. 2020)[^2]

This is described as a 1-dimensional model dervied as the limit of a 3-dimensional quantum system with strong confinement and including [[Spin-Orbit Coupling (SOC)]]. 

Like Michaeli et al. (2019)[^1], the model is simplified by confining the electron to a one-dimensional helixical path, reducing the spacial degrees of freedom to one. They then use adiabatic perturbation theory on this simplified geometry to understand the relationship between spin polarization effects and the geometry of the molecule. 

*Need to finish reading Giger et al. (2020)[^2] provides detailed description of different modeling approaches. *
#### References
[^1]: ![[@michaeli_origin_2019#^c49063]]
[^2]: ![[@geyer_effective_2020#^5f10d5]]