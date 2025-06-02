## ROBOKOP: Reasoning Over Biomedical Objects linked in Knowledge Oriented Pathways

### Introduction

ROBOKOP is a publicly available collection of harmonized biological, chemical, and medical knowledge bases.   These knowledge bases are created from other publicly available sources and transformed into a harmonized collection by the [ORION](http://github.com/ROBOKOPU24/ORION) pipeline.  These individual KGs are then merged into a single large KG: ROBOKOP KG.   Each source and aggregate graph is represented as a Knowledge Graph (KG), and each of these KGs is exposed with a common set of APIs.  The ROBOKOP KG can also be queried by a user-friendly interface ([qgraph](http://github.com/ROBOKOPU24/qgraph)).  The user interface and links to the APIs can be found at http://robokop.renci.org.

### Feedback

Please provide feedback on any aspect of the ROBOKOP project by going to the Feedback repository and logging an issue.

### Support

ROBOKOP is a joint creation of the [Renaissance Computing Institute (RENCI)](https://renci.org/) at the [University of North Carolina at Chapel Hill](https://www.unc.edu/) and [CoVar LLC](https://covar.com/). The prototype was developed with funding from the [National Center for Advancing Translational Sciences](https://ncats.nih.gov/), [National Institutes of Health](https://www.nih.gov/) (award [#OT2TR002514](https://taggs.hhs.gov/Detail/AwardDetail?arg_AwardNum=OT2TR002514&arg_ProgOfficeCode=264)). ROBOKOP's continued development is supported with joint funding from the [National Institute of Environmental Health Sciences](https://www.niehs.nih.gov/) and the [Office of Data Science Strategy](https://datascience.nih.gov/about/odss) within the [National Institutes of Health](https://www.nih.gov/) (award [#U24ES035214](https://tools.niehs.nih.gov/portfolio/index.cfm?do=portfolio.grantDetail&grant_number=U24ES035214)).

### Resources

Here are a few repositories of interest outside of the ROBOKOP org:
* [Biolink Model](https://github.com/biolink/biolink-model) is the data model used by ROBOKOP
* [Plater](https://github.com/TranslatorSRI/Plater) ingests a Biolink-compliant KG and exposes standard APIs
* [TRAPI](https://github.com/NCATSTranslator/ReasonerAPI) is the graph query API used by the NCATS Translator project.
* [Reasoner Transpiler](https://github.com/ranking-agent/reasoner-transpiler) converts TRAPI queries into cypher

### Architecture
![image](https://github.com/user-attachments/assets/376ab6da-3335-4d16-9f26-0aae454132d8)
