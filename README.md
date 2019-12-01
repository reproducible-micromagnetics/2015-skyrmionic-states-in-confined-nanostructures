# Ground state search, hysteretic behaviour and reversal mechanism of skyrmionic textures in confined helimagnetic nanostructures

Marijan Beg<sup>1</sup>, Rebecca Carey<sup>1</sup>, Weiwei Wang<sup>1</sup>,
David Cortés-Ortuño<sup>1</sup>, Mark Vousden<sup>1</sup>, Marc-Antonio
Bisotti<sup>1</sup>, Maximilian Albert<sup>1</sup>, Dmitri
Chernyshenko<sup>1</sup>, Ondrej Hovorka<sup>1</sup>, Robert L.
Stamps<sup>2</sup>, and Hans Fangohr<sup>1</sup>

<sup>1</sup> *Faculty of Engineering and the Environment, University of Southampton, Southampton SO17 1BJ, United Kingdom*  
<sup>2</sup> *SUPA School of Physics and Astronomy, University of Glasgow, G12 8QQ, Glasgow, United Kingdom*  

| Description | Badge                                                                                                                                                                                  |
| ---         | ---                                                                                                                                                                                    |
| Binder      | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/reproducible-micromagnetics/2015-skyrmionic-states-in-confined-nanostructures/master?filepath=index.ipynb) |
| License     | [![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)                                                              |

## Abstract (of the publication)

Magnetic skyrmions have the potential to provide solutions for low-power,
high-density data storage and processing. One of the major challenges in
developing skyrmion-based devices is the skyrmions’ magnetic stability in
confined helimagnetic nanostructures. Through a systematic study of equilibrium
states, using a full three-dimensional micromagnetic model including
demagnetisation effects, we demonstrate that skyrmionic textures are the lowest
energy states in helimagnetic thin film nanostructures at zero external magnetic
field and in absence of magnetocrystalline anisotropy. We also report the
regions of metastability for non-ground state equilibrium configurations. We
show that bistable skyrmionic textures undergo hysteretic behaviour between two
energetically equivalent skyrmionic states with different core orientation, even
in absence of both magnetocrystalline and demagnetisation-based shape
anisotropies, suggesting the existence of Dzyaloshinskii-Moriya-based shape
anisotropy. Finally, we show that the skyrmionic texture core reversal dynamics
is facilitated by the Bloch point occurrence and propagation.

## About this repository

This repository provides Ubermag simulation code to reproduce results from [Beg
*et al.* Ground state search, hysteretic behaviour and reversal mechanism of
skyrmionic textures in confined helimagnetic nanostructures. *Scientific
Reports*, **5**, 17137 (2015)](https://www.nature.com/articles/srep17137). All
notebooks hosted in this repository can be run in the cloud (see next section on
Binder), and thus the results reproduced by anybody.

## Reproducibility support

The key statement of the paper is that skyrmions are stable confirmations in confined geometries such as flat cylinders, even without crystal anisotropy and without applied fields. A central result of the work is figure 2 which shows for which applied field and which cylinder diametre a skyrmion is obtained as the lowest energy configuration and for which fields.

The production of figure 2 required to run many simulations, starting from different initial configurations for the magnetisation, minimising the system energy for each configuration, identify the resulting configuration with the lowest energy, and putting together a phase diagram that classifies the final configuration. 

The following notebook demonstrates how this calculation can be done for 2 points in the phase plane.

- [View the notebook statically: figure-02-ground-state.ipynb (nbviewer rendering)](https://nbviewer.jupyter.org/github/reproducible-micromagnetics/2015-skyrmionic-states-in-confined-nanostructures/blob/master/figure-02-ground-state.ipynb)
  ([github rendering](figure-02-ground-state.ipynb))
- [Interactively execute the notebook using Binder](https://mybinder.org/v2/gh/reproducible-micromagnetics/2015-skyrmionic-states-in-confined-nanostructures/master?filepath=figure-02-ground-state.ipynb)

## License

Licensed under the BSD 3-Clause "New" or "Revised" License. For details, please
refer to the [LICENSE](LICENSE) file.

## How to cite

Please cite paper as:

1. [Beg *et al.* Ground state search, hysteretic behaviour and reversal
   mechanism of skyrmionic textures in confined helimagnetic nanostructures.
   *Scientific Reports*, **5**, 17137
   (2015)](https://www.nature.com/articles/srep17137)

## Acknowledgements

Developed as a part of [OpenDreamKit](http://opendreamkit.org/) – Horizon 2020
European Research Infrastructure project (676541). This work was financially
supported by the EPSRC’s Doctoral Training Centre (DTC) grant EP/ G03690X/1.
R.L.S. acknowledges the EPSRC’s EP/M024423/1 grant support. D.C.-O. acknowledges
the financial support from CONICYT Chilean scholarship programme Becas Chile
(72140061). We acknowledge the use of the IRIDIS High Performance Computing
Facility and associated support services at the University of Southampton, in
the completion of this work. We also thank Karin Everschor-Sitte for helpful
discussions.
