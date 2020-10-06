---
title: Documentation
linkTitle: Documentation
cascade:
  type: documentation
  github_issue_filter: "label:\"standards - documentation\""
  github_issue_template: documentation.md
weight: 2
---

{{% standards-preamble %}}
These standards promote documentation needed for others to understand a model and reproduce its results.
{{% /standards-preamble %}}

## Overview of Documentation Standards

## Goals for Documentation Standards

Documentation of a model, together with the provided model code, needs to facilitate the understanding of the intentions of the developer, and make the model easier to test, use, and link to other models. It should also describe assumptions made about phenomena being modeled and what information is used to create and test the model.

We suggest three main categories of documentation:
- Metadata
- Methods and theoretical foundation
- Implementation

## Minimal Documentation Standards

### Metadata
- Name and version of the model
- Model project page (organizational website or repository, if available)
- Description of the model, including its purpose or goals and the type or formalism of the model  (e.g., system dynamic, agent based model, machine learning), preferably accompanied by relevant keywords
- Name(s) and contact information of the developer(s)/author(s)
- Date of release
- OSI-approved license
- How to cite the software
- Location where the model is posted or published (e.g. PID or DOI)
- Computer language or platform used for programming
- All software and/or hardware requirements needed to run the model and replicate any published results
- All data dependencies needed to run the model and replicate any published results
- Information on how to install the model so that it can be run (e.g., compilation and/or execution instructions)
- References to reports or publications where the model is used
- Changes since the last version (if the model is an update) including bug fixes, new features, or other substantive modifications, where appropriate.
- Link to other existing standards: 
    - e.g., Harpham, Q.K. and Danovaro, E. 2015. Towards standard metadata to support models and interfaces in a hydro-meteorological model chain, Journal of Hydroinformatics 17.2 260-274, IWA Publishing. doi: 10.2166/hydro.2014.061. https://doi.org/10.2166/hydro.2014.061
    - There is an iEMSs group looking at ideal documentation standards for numerical models.
    - Harpham, Q.K. 2020. A simple taxonomy for describing the spatio-temporal structure of environmental modelling data, Environmental Modelling and Software 133 104810, https://doi.org/10.1016/j.envsoft.2020.104810.

### Methods and theoretical foundation
- Assumptions: What are the key assumptions made that define the dynamics of the model?
- Model structure: provide a flow diagram of the model.
- Equations: What are the equations of the model?
- Temporal resolution, time stepping, and units 
- Spatial dimensionality, resolution, extent, grid type if relevant
- Limitations, domain ranges: What is this model specifically NOT intended to do.

### Implementation 

#### Input/Output and Variables 
- Key input parameters and their values and domain ranges and units (minimum input requirements for model operation and default values, where appropriate) 
- Initial conditions  
- Forcing functions that affect the dynamics of the model.  
- Control variables  
- Key output variables and domain ranges
- Provide sample runs that illustrate the dynamics of the model.

#### Validating installation
- Provide sample input and output files, including run script, such as a cookbook or benchmark

#### Model evaluation, uncertainty, and sensitivity
- Provide data used for calibration and evaluation of the model, if data are public. 
- Describe how calibration and evaluation to verify the accuracy of the model were performed. 
- List of publications on evaluation, uncertainty, sensitivity analyses for your model
- Describe or provide benchmarks for validation of your model

## Ideal Documentation Standards

## Cyberinfrastructure and Tools for Implementation of Documentation Standards
- e.g., doxygen


## Examples and References for Documentation



