<!--lint disable awesome-heading-->
<p align="center">
  <img src="https://www.ohdsi.org/wp-content/uploads/2015/02/h243-ohdsi-logo-with-text.png" alt="OHDSI Logo" width="400"/>
</p>

<h1 align="center">Awesome OHDSI</h1>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://github.com/OMOPHub/awesome-ohdsi/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg" alt="License: CC0-1.0"></a>
  <a href="https://github.com/OMOPHub/awesome-ohdsi/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
</p>

<p align="center">
  A curated list of awesome <a href="https://ohdsi.org">OHDSI</a> (Observational Health Data Sciences and Informatics) tools, packages, resources, and community projects for working with the <a href="https://ohdsi.github.io/CommonDataModel/">OMOP Common Data Model</a>.
</p>

<p align="center">
  <sub>Contributions welcome! Read the <a href="CONTRIBUTING.md">contribution guidelines</a> first.</sub>
</p>

---

## Contents

- [Official Resources](#official-resources)
- [Core OHDSI Tools](#core-ohdsi-tools)
- [HADES R Packages](#hades-r-packages)
  - [Data Quality](#data-quality)
  - [Characterization](#characterization)
  - [Population-Level Estimation](#population-level-estimation)
  - [Patient-Level Prediction](#patient-level-prediction)
  - [Evidence Synthesis](#evidence-synthesis)
- [Vocabulary Tools](#vocabulary-tools)
- [ETL & Data Transformation](#etl--data-transformation)
- [Python Tools](#python-tools)
- [Visualization & Dashboards](#visualization--dashboards)
- [Infrastructure & Deployment](#infrastructure--deployment)
- [FHIR Integration](#fhir-integration)
- [Sample Data & Testing](#sample-data--testing)
- [Learning Resources](#learning-resources)
- [Community](#community)

---

## Official Resources

*Official OHDSI websites, documentation, and community resources.*

- [OHDSI Website](https://ohdsi.org) - Official OHDSI organization website.
- [The Book of OHDSI](https://ohdsi.github.io/TheBookOfOhdsi/) - Comprehensive guide to OHDSI methods and tools.
- [OMOP CDM Documentation](https://ohdsi.github.io/CommonDataModel/) - Official Common Data Model specification.
- [ATHENA](https://athena.ohdsi.org/) - OHDSI standardized vocabularies browser and download.
- [OHDSI Forums](https://forums.ohdsi.org/) - Community discussion forums.
- [OHDSI GitHub](https://github.com/OHDSI) - Official OHDSI repositories.
- [HADES](https://ohdsi.github.io/Hades/) - Health Analytics Data-to-Evidence Suite documentation.

## Core OHDSI Tools

*Essential tools for working with OMOP CDM data.*

- [ATLAS](https://github.com/OHDSI/Atlas) - Web-based tool for cohort definition, characterization, and study design.
- [WebAPI](https://github.com/OHDSI/WebAPI) - Backend services for ATLAS providing REST APIs for OMOP CDM.
- [Achilles](https://github.com/OHDSI/Achilles) - Database characterization and data quality tool that powers ATLAS Data Sources.
- [Usagi](https://github.com/OHDSI/Usagi) - Application for mapping source codes to OMOP standard concepts.
- [WhiteRabbit](https://github.com/OHDSI/WhiteRabbit) - Tool for profiling source data before ETL.
- [RabbitInAHat](https://github.com/OHDSI/WhiteRabbit) - ETL design and documentation tool (bundled with WhiteRabbit).
- [Perseus](https://github.com/OHDSI/Perseus) - Web-based vocabulary mapping tool.
- [DataQualityDashboard](https://github.com/OHDSI/DataQualityDashboard) - Tool to evaluate data quality of OMOP CDM instances.

## HADES R Packages

*R packages from the Health Analytics Data-to-Evidence Suite.*

### Data Quality

- [DataQualityDashboard](https://github.com/OHDSI/DataQualityDashboard) - Evaluate and visualize data quality.
- [Achilles](https://github.com/OHDSI/Achilles) - Database characterization and profiling.
- [DbDiagnostics](https://github.com/OHDSI/DbDiagnostics) - Database diagnostics for OMOP CDM.

### Characterization

- [FeatureExtraction](https://github.com/OHDSI/FeatureExtraction) - Extract features from OMOP CDM for machine learning.
- [Characterization](https://github.com/OHDSI/Characterization) - Cohort characterization studies.
- [CohortDiagnostics](https://github.com/OHDSI/CohortDiagnostics) - Evaluate cohort definitions.
- [OmopSketch](https://github.com/OHDSI/OmopSketch) - Quickly characterize and visualize OMOP CDM instances.

### Population-Level Estimation

- [CohortMethod](https://github.com/OHDSI/CohortMethod) - New-user cohort studies for causal effect estimation.
- [SelfControlledCaseSeries](https://github.com/OHDSI/SelfControlledCaseSeries) - Self-controlled case series analysis.
- [SelfControlledCohort](https://github.com/OHDSI/SelfControlledCohort) - Self-controlled cohort design.
- [CaseControl](https://github.com/OHDSI/CaseControl) - Case-control studies.
- [CaseCrossover](https://github.com/OHDSI/CaseCrossover) - Case-crossover design.
- [EvidenceSynthesis](https://github.com/OHDSI/EvidenceSynthesis) - Meta-analysis and evidence synthesis.

### Patient-Level Prediction

- [PatientLevelPrediction](https://github.com/OHDSI/PatientLevelPrediction) - Build and validate patient-level prediction models.
- [DeepPatientLevelPrediction](https://github.com/OHDSI/DeepPatientLevelPrediction) - Deep learning extensions for PLP.
- [EnsemblePatientLevelPrediction](https://github.com/OHDSI/EnsemblePatientLevelPrediction) - Ensemble methods for PLP.

### Evidence Synthesis

- [EvidenceSynthesis](https://github.com/OHDSI/EvidenceSynthesis) - Combine evidence from multiple studies.
- [Cyclops](https://github.com/OHDSI/Cyclops) - Large-scale regularized regression.

### Database Connectivity

- [DatabaseConnector](https://github.com/OHDSI/DatabaseConnector) - Connect R to various database platforms.
- [SqlRender](https://github.com/OHDSI/SqlRender) - Translate SQL across database dialects.
- [Eunomia](https://github.com/OHDSI/Eunomia) - Standard dataset manager for sample OMOP CDM datasets.

## Vocabulary Tools

*Tools for working with OHDSI standardized vocabularies.*

- [ATHENA](https://athena.ohdsi.org/) - Official vocabulary browser and download service.
- [Usagi](https://github.com/OHDSI/Usagi) - Semi-automated vocabulary mapping.
- [Perseus](https://github.com/OHDSI/Perseus) - Web-based vocabulary mapping.
- [OMOPHub Python SDK](https://github.com/OMOPHub/omophub-python) - Python client for querying ATHENA vocabularies via API.
- [OMOPHub R SDK](https://github.com/OMOPHub/omophub-R) - R client for querying ATHENA vocabularies via API.
- [omopcept](https://github.com/darwin-eu/omopcept) - R package for accessing OMOP concepts with tidyverse-compatible functions.

## ETL & Data Transformation

*Tools for transforming source data to OMOP CDM.*

- [WhiteRabbit](https://github.com/OHDSI/WhiteRabbit) - Source data profiling for ETL planning.
- [RabbitInAHat](https://github.com/OHDSI/WhiteRabbit) - ETL specification and documentation.
- [ETL-CDMBuilder](https://github.com/OHDSI/ETL-CDMBuilder) - .NET application for ETL to OMOP CDM.
- [carrot](https://github.com/Health-Informatics-UoN/carrot) - Streamlined data transformation to OMOP.
- [carrot-mapper](https://github.com/Health-Informatics-UoN/carrot-mapper) - Streamlined data mapping to OMOP.
- [carrot-transform](https://github.com/Health-Informatics-UoN/carrot-transform) - Streamlined data transformation to OMOP.
- [oxford-omop-data-mapper](https://github.com/answerdigital/oxford-omop-data-mapper) - DuckDB-based ETL tool for clinical datasets.
- [Eos](https://github.com/SevKohler/Eos) - ETL engine to transform openEHR into OMOP.
- [kotobuki](https://github.com/thehyve/kotobuki) - Update Usagi mappings programmatically.
- [convert-pheno](https://github.com/CNAG-Biomedical-Informatics/convert-pheno) - Interconversion of standard phenotypic data models including OMOP.

## Python Tools

*Python libraries and tools for OMOP CDM.*

- [OMOPHub Python SDK](https://github.com/OMOPHub/omophub-python) - Query ATHENA vocabularies via API.
- [dzd-omop-cdm-python-models](https://github.com/DZD-eV-Diabetes-Research/dzd-omop-cdm-python-models) - Python/Pydantic/SQLAlchemy data class representation of OMOP CDM.
- [omop-learn](https://github.com/clinicalml/omop-learn) - Machine learning pipelines for OMOP CDM data.

## Visualization & Dashboards

*Tools for visualizing OMOP CDM data.*

- [Cohort360](https://github.com/aphp/Cohort360-FrontEnd) - Web application for cohort building and health record visualization.
- [omopcat](https://github.com/SAFEHR-data/omopcat) - Summary of OMOP data with public data catalogue.
- [Data2Evidence](https://github.com/OHDSI/Data2Evidence) - End-to-end solution for management and analysis of OMOP data.
- [OmopSketch](https://github.com/OHDSI/OmopSketch) - Characterize and visualize OMOP CDM instances.

## Infrastructure & Deployment

*Tools for deploying OHDSI infrastructure.*

- [OHDSIonAWS](https://github.com/OHDSI/OHDSIonAWS) - Deploy OHDSI toolstack on AWS.
- [Broadsea](https://github.com/OHDSI/Broadsea) - Docker-based deployment of OHDSI tools.
- [OHDSI-in-a-Box](https://github.com/OHDSI/OHDSI-in-a-Box) - Single-server OHDSI learning environment.
- [CommonDataModel](https://github.com/OHDSI/CommonDataModel) - DDL scripts for creating OMOP CDM tables.

## FHIR Integration

*Tools bridging FHIR and OMOP.*

- [OMOP on FHIR](https://github.com/omoponfhir) - FHIR server backed by OMOP CDM.
- [recruit](https://github.com/miracum/recruit) - Clinical trial recruitment system using FHIR and OMOP.
- [cql-on-omop](https://github.com/umg-minai/cql-on-omop) - Apply CQL libraries to OMOP databases.

## Sample Data & Testing

*Sample datasets and testing tools.*

- [Eunomia](https://github.com/OHDSI/Eunomia) - Standard dataset manager with sample OMOP CDM datasets.
- [SynPUF](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs) - CMS synthetic patient data.
- [Synthea](https://github.com/synthetichealth/synthea) - Synthetic patient generator (can output to OMOP).
- [ETL-Synthea](https://github.com/OHDSI/ETL-Synthea) - ETL from Synthea to OMOP CDM.

## Learning Resources

*Tutorials, courses, and educational materials.*

- [The Book of OHDSI](https://ohdsi.github.io/TheBookOfOhdsi/) - Comprehensive guide covering all aspects of OHDSI.
- [OHDSI Academy](https://ohdsi.org/ohdsi-academy/) - Free online courses and tutorials.
- [HADES Documentation](https://ohdsi.github.io/Hades/) - Package documentation and tutorials.
- [OHDSI YouTube](https://www.youtube.com/c/OHDSI) - Video tutorials and community calls.
- [Guide to N3C](https://github.com/rwdcollaborative/guide-to-n3c-v1) - Research with the National COVID Cohort Collaborative.

## Community

*OHDSI community resources.*

- [OHDSI Forums](https://forums.ohdsi.org/) - Ask questions, share knowledge.
- [OHDSI Teams](https://ohdsi.org/join-the-community/) - Real-time community chat.
- [OHDSI Symposium](https://www.ohdsi.org/ohdsi-symposium/) - Annual conference.
- [OHDSI Working Groups](https://ohdsi.org/who-we-are/workgroups/) - Contribute to specific areas.
- [OHDSI Studies](https://github.com/ohdsi-studies) - Network study repositories.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related rights to this work.
