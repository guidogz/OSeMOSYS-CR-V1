---
title: 'OSeMOSYS-CR: Energy System Optimization Model for Costa Rica'
tags:
  - Energy Policy
  - Energy Modelling
  - Energy System Optimization Model
  - Deep Decarbonization
  - OSeMOSYS
authors:
  - name: Guido Godínez-Zamora
    orcid: 0000-0002-0256-1640
    affiliation: 1
  - name: Luis Victor-Gallardo
    affiliation: 1
  - name: Jam Angulo-Paniagua
    affiliation: 1
  - name: Eunice Ramos
    affiliation: 2
  - name: Mark Howells2
    affiliation: 2
  - name: Will Usher
    affiliation: 2
 - name: Felipe De León
    affiliation: 3
 - name: Jairo Quirós-Tortós
    affiliation: 1

affiliations:
 - name: School of Electrical Engineering, University of Costa Rica, San José, Costa Rica
   index: 1
 - name: Division of Energy Systems Analysis, KTH Royal Institute of Technology, Stockholm, Sweden.
   index: 2
- name: Climate Change Directorate, Ministry of Environment and Energy, San José, Costa Rica.
   index: 3
date: 30 January 2020
bibliography: paper.bib

# Optional fields if submitting to a AAS journal too, see this blog post:
# https://blog.joss.theoj.org/2018/12/a-new-collaboration-with-aas-publishing
aas-doi: 10.3847/xxxxx <- update this with the DOI from AAS once you know it.
aas-journal: Astrophysical Journal <- The name of the AAS journal.
---

# Summary

Costa Rica has an extensive tradition of nature protection and leadership to fight climate
change. With an almost 100% renewable electricity matrix and forest coverage of approximately 60%, the country is moving toward the transformation of the transport sector as the third major step towards decarbonisation. This sector represents 44% of the total Greenhouses Gases (GHG) emission of the country. In this context, through the alliance between the government and the academia, the OSeMOSYS-CR model was developed by the University Costa Rica, The Royal Institute of Technology and the Climate Change Directorate as part of the Deep Decarbonization Pathways Project in Latin America and the Caribbean (DDPP-LAC), which is coordinated by the Institute for Sustainable Development and International Relations (IDDRI) and the Inter-American Development Bank (IADB) [IDB2019]. As a result, the model helped to formulate and analyze the National Decarbonisation Plan of Costa Rica (NDP) [MINAE2019], which is the long-term low-level GHG strategy of the country, representing an advance in terms of transparency and the decision-making process.
OSeMOSYS-CR is an Energy System Optimization Model (ESOM), based on Open Source Energy Modelling System (OSeMOSYS) [HOWELLS20115850,GARDUMI2018209] that follows a bottom-up approach to establishing the most cost-effective technological transitions towards a deep decarbonisation in the energy sector, with special attention to transportation, which is crucial for understanding the technological transition of fossil-fuel vehicles to lower or zero emissions option. The model was built on a countrywide scale considering the effect of rainy and dry months and including the entire process from energy sources supply to demands. The entire composition was based on the best available data and selecting control variables to monitor the reliability of the model, such as the sale of fossil fuels and electricity or the relation between the average distance travelled and energy consumption for the transport sector.
The Figure 1 present how primary energy supply (i.e. renewable, fossil fuel imports, biomass and electricity imports) are transformed into different modes of energy through technologies that include power plants, vehicles and distribution systems. These transformations meet the industrial, residential, commercial and agricultural energy requirements, and the transport of passengers or cargo demands. A module for co-benefits related to the activity of fossil fuels calculates the effects on health, congestion, and the number of accidents. The model combines more than one hundred commodities and two hundred technologies. The entire composition was based on the best available data and selecting control variables to monitor the reliability of the model, such as the sale of fossil fuels and electricity or the relation between the average distance travelled and energy consumption for the transport sector. Each of the elements in the model is properly specified by costs, emissions, activity, and capacity parameters, as appropriate. Every parameter was chosen after an exhaustive search of mostly national data such as: energy demands per sector, planning and operation studies, cost of infrastructures and technologies, number and type of vehicles and the average of traffic flow. A documentation of these parameters is also included in the repository. 


#The forces on stars, galaxies, and dark matter under external gravitational 
#fields lead to the dynamical evolution of structures in the universe. The orbits
#of these bodies are therefore key to understanding the formation, history, and
#uture state of galaxies. The field of "galactic dynamics," which aims to model
#the gravitating components of galaxies to study their structure and evolution,
#is now well-established, commonly taught, and frequently used in astronomy.
#Aside from toy problems and demonstrations, the majority of problems require
#efficient numerical tools, many of which require the same base code (e.g., for
#performing numerical orbit integration).

#``Gala`` is an Astropy-affiliated Python package for galactic dynamics. Python
#enables wrapping low-level languages (e.g., C) for speed without losing
#flexibility or ease-of-use in the user-interface. The API for ``Gala`` was
#designed to provide a class-based and user-friendly interface to fast (C or
#Cython-optimized) implementations of common operations such as gravitational
#potential and force evaluation, orbit integration, dynamical transformations,
#and chaos indicators for nonlinear dynamics. ``Gala`` also relies heavily on and
#interfaces well with the implementations of physical units and astronomical
#coordinate systems in the ``Astropy`` package [@astropy] (``astropy.units`` and
#``astropy.coordinates``).

#``Gala`` was designed to be used by both astronomical researchers and by
#students in courses on gravitational dynamics or astronomy. It has already been
#used in a number of scientific publications [@Pearson:2017] and has also been
#used in graduate courses on Galactic dynamics to, e.g., provide interactive
#visualizations of textbook material [@Binney:2008]. The combination of speed,
#design, and support for Astropy functionality in ``Gala`` will enable exciting
#scientific explorations of forthcoming data releases from the *Gaia* mission
#[@gaia] by students and experts alike.

# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$


# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this: ![Example figure.](figure.png)

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References
