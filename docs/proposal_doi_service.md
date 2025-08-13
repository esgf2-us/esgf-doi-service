# Proposed ESGF DOI Service

## Background:
Digital Object Identifiers (DOI) is a digital identifier to uniquely identify digital objects, such as datasets in ESGF.

A review of data citation service requirements for CMIP was conducted by Stockhause et. al. 2024 and provided recommendations for a sustainable data citation service.

>Stockhause, M., Ames, S., Dingley, B., Lawrence, B., Liang, H.-C., Liu, Y., Parton, G. and Radhakrishnan, A. (2024). Recommendations for a sustainable data citation service for CMIP. [online] Zenodo. Available at: [https://doi.org/10.5281/zenodo.13748704](https://doi.org/10.5281/zenodo.13748704).

## Objective:
Objective of ESGF DOI service is to offer an service for DOI
registration for CMIP7 datasets, maintain landing pages, and integrate
with data publication workflows. The service is expected to be available
for all projects under `mip_era = CMIP7`, including `input4MIPs` and
`obs4MIPs`. DOIs from ESGF DOI Service is however optional, and data
producers/modeling centers can choose to use their own DOIs.

## Proposed Workflow:
Proposed below is an workflow that can be designed and maintained by
ESGF2-US team. ESGF2-US will leverage 
[US Department of Energy's (DOE) DATA ID
Service](https://www.osti.gov/pids/doi-services/doe-data-id-service)
that registers the DOIs with [DataCite](https://www.datacite.org/) to aid 
in citation, discovery, retrieval, and reuse. 

Flowchart below provides an overview of the proposed DOI service.

<img src="doi_workflow.png" alt="DOI service workflow" width="800" height="500">

%![DOI service workflow](doi_workflow.png)

