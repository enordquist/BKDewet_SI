# BKDewet_SI
Plumed run files for metadynamics and umbrella sampling N_{water} in BK channel inner pore.
Also a representative mdp file for NPT dynamics with protein Calpha restraints.

Pressure fluctuations can result with the combination of restraints and Parrinello-Rahman barostat in
gromacs, so perhaps try using refcoord_scaling, adjust tau_p, or use the berendsen barostat if your system
is small. For another set of examples corresponding to our earlier metadynamics paper using
model nanopores and much smaller solvent boxes, see [enordquist/poredewet_SI repo](https://github.com/enordquist/poredewet_SI).

These files are used in relation to:
Nordquist E, Jia Z, Chen J. Inner pore hydration free energy controls the activation of big potassium channels. Biophys. J. 2023, 122, 1158-1167. DOI: [10.1016/j.bpj.2023.02.005](10.1016/j.bpj.2023.02.005)
