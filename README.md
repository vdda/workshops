BICONTAINERS HACKTHON 2017: Reproducible Bioinformatics
---------------------------------------------------------

- Date: 9-11 October 2017
- Place: To be defined soon: Paris, France
- [BioHachathon Workshop: Eventbrite Registration](https://www.eventbrite.co.uk/e/biocontainers-hackathon-reproducible-bioinformatics-tickets-35601135956)

## Purpose

The “ELIXIR Software Deployment Group” is one of the six working groups of the ELIXIR tools platform. It has been recently formed to support bioinformatics software deployment efforts including packages and containers. At the moment this group is sustained by ELIXIR Nodes sharing common interest to work together on a harmonised strategy. The activities of this group are extremely relevant to other two groups within ELIXIR Tools platforms: “Workflows & workbenches” and “Software development best practices” because it represents the starting point for the development of reproducible pipelines and workflows in bioinformatics.

This group would like to accelerate and consolidate the Containers platform as a Service, and the integration with other groups like Workflows & workbenches and Software tools (Bio.Tools) as defined in the ELIXIR work plan 2017. To do so we proposed to have a 2.5 days hackathon. In practice the hackathon will give us the opportunity to work in four different topics:

- Consolidate the integration between: Biocontainers [1] (biocontainers.pro), BioConda (https://bioconda.github.io/) and Bioshadock [2] (http://bioshadock.genouest.org/) initiatives.
- Define the future architeture of BioContainers: Containers registry, Containers Automatic Deplyment Systems. Also the integration with Bio.tools and Workflow systems such as Galaxy and CWL.
- Improve the metadata definition for BioContainers/BioConda.
- In addition, we will define a strategy (Metadata) for “Training Containers”, design an infrastructure for hosting containers in ELIXIR and engage the training community to create containers for training purposes. We will start developing containers for training.

## Current Agenda

### October 9  - 2017

- Registration & Welcome, Introduction (Someone from Host)
- **Talk**: BioContainers: Current Status and Challenges (**Yasset Perez-Riverol, EMBL-EBI, UK**)
- **Talk**: Invited Speaker
- **Talk**: ELIXIR Training (Invited Speaker)
- **Talk**: Mulled: Automatic Creation of Dockerfile-free BioContainers (**Bjorn, Freiburg, Germany**)
- **Talk**: Dockerfile - based BioContainers: (**Olivier Sallou, France**)
- Planning of the Activities for 2 days Hackathon (**Yasset Perez-Riverol, EMBL-EBI, UK**)

#### Hackathon Topics:
 - Containers (BioContainers) and Packages (BioConda) Specification:
   - Metadata: Minimun Metadata, Base Images and Versioning.
   - Metadata for Training Containers.
   - Metadata Validator.

 - BioContainers Deployment Architecture:
   - Mulled BioContainers Architeure: Current Struture and Improvements.
   - DockerFile-based Biocntainers Architecture: Current Structure and Improvements.

 - **Hackathon**: Review of current BioContainers:
   - Solve Duplications, broken and non-functional containers.
   - Create and Build current requested Containers.
   - Creation of Training Containers.
   - Training session on BioContainers and Containers in BioInformatics

 - Poster Sessions & Use Cases Collections
 - **Wrap-up of the session**

### October 10 - 2017

- Talk: Galaxy Workflows integration with Containers. (**Bjorn, Freiburg, Germany**)
- Talk: Invited Speaker
- Talk: BioContainers Registries, Deployment (**Yasset Perez-Riverol, EMBL-EBI, UK**)

#### Hackathon Topics:

- Singularity Images.

- Workflows and BioContainers:
  - Automatic creation of MultiContainers.
  - Workflow dependency conversion to MuntiBioContainer.
  - Annotation/Storage of Multi-Containers.
  - Examples and Best Practices Guidelines for multiple-tools containers.

- BioContainers/Conda Registry:
  - Improvements of Metadata Search.
  - Reimplementation to handle BioConda/BioContainers/Singularity recipies.
  - Registry API.
  - CLI tool with same campabilities that the Web Interface.

- **Hackathon**: Creation of Training Containers.
- Poster Sessions & Use Cases Collections.
- **Wrap-up of the session**

### October 11 - 2017

- Engagement with Community/Insdustry/Journals
- Publications RoadMap and Grants/Fundings Posibilities
- ELIXIR Software Deployment Group & BioContainers Group
  - Organization
  - RoadMap
  - Integration with other Initiatives.
  - Plans for 2018.

- Conclusions and Wrap-up of the Hackathon.


## Bibliography
[1] Leprevost, F. D. V.; Grüning, B. A.; Aflitos, S. A.; Röst, H. L.; Uszkoreit, J.; Barsnes, H.; Vaudel, M.; Moreno, P.; Gatto, L.; Weber, J.; et al. BioContainers: an open-source and community-driven framework for software standardization. Bioinformatics 2017.

[2] Moreews, F.; Sallou, O.; Ménager, H.; Bras, Y. L.; Monjeaud, C.; Blanchet, C.; Collin, O. BioShaDock: a community driven bioinformatics shared Docker-based tools registry. F1000Research 2015.
