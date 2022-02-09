# Pixhawk AADL Case Study

AADL models for the Pixhawk UAV, demonstrating various AADL toolchains

***Note:*** This model is used as part of Binghamton Senior Project ECD205 UAV Fabrication and Modeling.

## About

This set of models has been built as part of various classes on AADL.
This model captures the high-level elements of the [Crazyflie
UAV](https://www.bitcraze.io) by the bitcraze. It aims at illustrating
basic CPS designs capabilities of AADL: model construction, analysis
(flow latency, schedulability, fault analysis, code generation, ...)

This project has been defined to work properly with
[OSATE](http://osate.org)

## Structure

This model is organized as follows
- `diagrams`: graphical representation of the models, used by OSATE
- `library`: reusable AADL models
- `models`: core AADL models of the Crazyflie UAV

## Use with OSATE

### Import

Simply import the GitHub project directly from OSATE, using the following menus:

  `File` -> `Import` -> `Git` -> `Projects from Git`

then, indicate the project URI

### Available analysis

The following capabilities of OSATE are demonstrated:
- text editing
- graphical model browsing/editing
- flow latency analysis
- fault analysis, including fault tree analysis

This model has been tested with

|Tool           | Version |
|---------------|---------|
| OSATE         | 2.7.0   |

