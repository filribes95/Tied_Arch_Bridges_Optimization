# Optimizing Tied-Arch Bridges for Sustainability: A Study on Arch Size and Shape Modification
[![DOI](https://zenodo.org/badge/736339592.svg)](https://zenodo.org/doi/10.5281/zenodo.10450706)

## Abstract
In a world focused on environmental sustainability, optimizing the design of road bridges not only brings economic advantages but also plays a crucial role in promoting a greener and more environmentally conscious future. Utilizing optimization algorithms and parametric designs is a pivotal key in achieving this objective, allowing us to design infrastructures that are both sustainable and resilient, especially those characterized by a significant amount of carbon dioxide emissions (CO2) like bridges. To address this need, we developed an optimization algorithm that assesses the environmental impact of tied-arch bridges, a common infrastructure type worldwide. Our algorithm focuses on the arch’s geometry, particularly its shape and cross-sections, and it is tailored to road bridges made of steel that are straight and have a deck with constant length and width. To evaluate our system, we studied an existing tied-arch bridge and its arch’s steel usage, cost and CO2 equivalent emissions. In order to formulate an optimization plan, these metrics were then compared with those of five different variations of the same bridge with altered parameters generated with the algorithm. The results of the studied variants confirm the actual design quality of the analyzed bridge, but suggest a non-negligible potential for carbon dioxide reduction of up to 6.80 %.

## Key Topics
- Structural design and optimization of tied-arch bridges
- Finite element modeling (FEM)
- Python development for optimization algorithms
- Comparative analysis of bridge designs
- Environmental impact assessment

## Methods
The algorithm is employed to optimize the bridge structure through the examination of various alternative designs proposed by minimizing the steel usage, resulting in costs and CO2 emissions reduction. The purpose of our algorithm is not to produce complete designs or accurate estimates of the results; rather, it should point in the right direction and help the designer to quickly find a good solution. To reach this goal, an existing tied-arch bridge was taken as the focus of this study. The following flowchart explains and resume how each alternative design is made.

![immagine](https://github.com/filribes95/Tide_Arch_Bridges_Optimization/assets/141939096/79edd1ce-bac5-4ed6-91ff-54e197139f3f)

## Results
The optimized designs shall not only be cost-effective and environmentally friendly but also feasible and realistic. Therefore, five different scenarios, each characterized by its rise to span ratio (f/l), were proposed to optimize an existing tied-arch bridge and the results, in terms of steel usage, cost, and CO2 emissions, were compared.

![immagine](https://github.com/filribes95/Tide_Arch_Bridges_Optimization/assets/141939096/dde6be41-6b3a-4b69-b624-464fbc9e6aa8)

![immagine](https://github.com/filribes95/Tide_Arch_Bridges_Optimization/assets/141939096/cad41d02-15c7-4091-bde2-d5b37eda09eb)

![immagine](https://github.com/filribes95/Tide_Arch_Bridges_Optimization/assets/141939096/2b7c4331-c756-4c40-8259-6c9ac1e7ef10)

## Conclusion
This document has presented an optimization process tailored for assessing and optimizing the environmental impact of tied-arch bridges. Central to this process was the calculation of steel quantities used in construction, alongside associated costs and CO2 emissions. Focusing on the arch’s shape and cross-sectional geometries, a real-life existing bridge was analyzed and compared against alternative designs with varied arch configurations. Notably, one of these alternatives achieved a significant maximum saving of 6.80 % compared to the original design. This result not only underscores the high quality of the original design but also validates the feasibility and potential for meaningful optimization in similar case studies.

## How to Use
This repository includes the full thesis document, the FEM of the bridge made in Strand7 (.st7), the arch shape and size parametrization made in Excel and the Python code used for the optimization processes.

## Author
Filippo Ribes
