<b>Project Charter for AralDIF, A Cloud-based Dynamic Information Framework for Water Resources Management in the Aral Sea basin</b>
 
<b><i>Vision</i></b>
 
A Dynamic Information Framework (DIF) is a decision support structure centered on earth system science models and data resources. DIF can serve as a tool to address policy challenges in water resources caused by population growth, socio-economic development and climate change, particularly in developing nations.

A core component of the DIF is the hydrological model VIC. The use of VIC requires data layers that can be harnessed from a plethora of existing datasets e.g. NASA, Earthcube, NOAA and various reanalysis products. We want to automate the assimilation of all these datasets into a database that can be flexible enough to be expanded as needed.
 
The datasets and the modeled outputs from VIC also need to visualized in a way that is both interactive and comprehensible but technical enough for stakeholders in the Central Asia region to use in shaping policy to address challenges in water resources management. Stakeholder interactions have stressed the need for a user-friendly interface of VIC. 
 
 
<b><i>Objectives</i></b>
The specific objectives for this project are:

1.     Database Architecture
The first task in building out AralDIF is to architect a database backend that will provide both the core support for the VIC hydrological model and that anticipates expansion to other forms, formats and sources of geospatial data. This database contains all the information that goes into the models: geographical layers such as landcover schemes and topography, gridded datasets for climate forcings and so on. The database should ideally be flexible enough to be expanded as needed and easily ported from domain to domain without having to start over from scratch.
 
2.     Model to cloud including API & GUI
We will deploy VIC in the cloud and create a web-based GUI (wrapped with an existing framework such as Django) that will allow users to understand the modeling environment. The user will be able to specify several set parameters in order to test the model.
 
3.     Visualization
Model inputs and outputs must be comprehensible to the end user to build confidence in DIF. We will create an automated visualization pipeline that displays model results in both a scientific way for technical specialists and interactively for decision makers is needed
 
<b><i>Success Criteria</i></b>

·      A functioning database containing all the necessary data to run VIC on the cloud that can use

·      A web-based VIC GUI interface that accepts parameter inputs

·      Visualization of data layers (both inputs to the model and output of model)
 
<b><i>Deliverable Schedule</i></b>

Jan. 26 All datasets and data layers to be made available in the cloud

Feb. 15 VIC GUI test

Feb. 29 Database trial – end user able to push/pull data

Mar. 5 Visualization pipeline complete

Mar. 10 Final presentation
