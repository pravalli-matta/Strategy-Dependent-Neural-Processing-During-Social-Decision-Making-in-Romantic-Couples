# Strategy-Dependent Neural Processing During Social Decision-Making in Romantic Couples

This project involved an exploratory analysis of an open-access fMRI dataset from a social decision-making task involving romantic couples. It was completed as part of the Human Brain Mapping course at IIT Gandhinagar (2026).

## Background

Decisions within a couple can involve different strategies, such as yielding to a partner or insisting on one's own preference. The dataset provides an opportunity to examine brain activity associated with these interpersonal decision conditions.

## Analysis Questions

The analysis focused on contrasts between:

- **Yield > Insist**
- **Agree > Disagree**

These contrasts were used to examine differences in BOLD responses associated with the task conditions. They should be understood as task-based comparisons, not as direct measures of broad relationship quality or stable decision-making traits.

## Analysis Workflow

The analysis was carried out using FSL FEAT and included:

1. Preparing first-level general linear models (GLMs).
2. Modelling task events with regressors convolved with the haemodynamic response function (HRF).
3. Inspecting registration quality and model diagnostics.
4. Reviewing carpet plots and correlations with nuisance regressors as part of quality control.
5. Screening event timings and condition labels.
6. Examining contrast maps in MNI space and interpreting their anatomical locations with reference to the Harvard–Oxford atlas.

## Interpretation and Limitations

The work is an exploratory, subject-level analysis of an existing dataset. The number and distribution of usable events, along with the scope of the analysis, limit the strength of conclusions that can be drawn. The contrasts describe differences associated with the modelled task conditions; they do not by themselves establish causal mechanisms, explain relationship outcomes, or support broad claims about all romantic couples.

## Report

[Read the project report (PDF)](Strategy-Dependent%20Neural%20Processing%20During%20Social%20Decision-Making%20in%20Romantic%20Couples.pdf)

## Methods and Tools

fMRI, FSL FEAT, first-level GLM, HRF-convolved task regressors, registration quality control, nuisance-regressor inspection, MNI space, and Harvard–Oxford atlas.

## Project Details

- **Course:** Human Brain Mapping
- **Institution:** IIT Gandhinagar
- **Instructor:** Prof. Vaibhav Tripathi
- **Year:** 2026
- **Author:** Pravalli Matta
