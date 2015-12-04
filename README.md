This is JCBN's Fork of the final project

Quick Link to see visualization: https://rawgit.com/Jcbnunez/finalproject/master/finalproject.html

Presentation Mode: https://rawgit.com/Jcbnunez/finalproject/master/finalproject_presentation.html
_____________

# Final Project

## Instructions

This repository is a stub for your final project. Fork it as a template for your project, and develop your code in the forked repository. For details on how to fork and turn in the project, see section 3 of the github education  [documentation](https://education.github.com/guide/forks). After you fork the repository, please enable the issue tracker in the repository settings so that others in the class (including the professor) can provide feedback.

Expand on the readme questions below to provide an overview of the goals, background, and challenges for the final project. You can delete the questions as you write text that answers them, or leave the prompts in place. You can also delete this instruction section of you like.

## Introduction

This is a final project for the [Interacting with Data](https://github.com/Brown-BIOL2430-S04-Fall2015/syllabus) seminar in fall 2015. This project seeks to produce an interactive visualization for real genetic data and it relationship with an ecological variable that behaves ina  clinal fashion. 

Some visualizations of genetic data tend to decouple the ecological or geographical variables with genetic variables, often showing them as individual plots. This is not detrimental to the science as the reader has the power to use the information form individual plots and see patterns among all the data. However, the idea of this visualization is to ease the incorporation of genetic and ecological or geographical data into single informative plots with multiple graphical elements.    

To view this project please visit https://rawgit.com/Jcbnunez/finalproject/master/finalproject.html

## The data

Description of data...

- Data source: Unpublished genetic variation data from fish. As it is unpublished, data has been anonymized  
- Data structure: The data encompasses mesures of variation with estimates of statistical confidence. The data is available for 7 populations across an ecological gradient. The data also described complete genome estimates of variation and gene by gene estimates (for 7 genes).   

## Background

Previous visualization of these data were mostly two-dimentional and static. This is, in order to fully explore the data the reader had to parse together mutiple 2D graphs of estimates of the whole chromosome and all individual genes. Also the geographic component of the data was althoghther excluded. 

This visualization addresses the shortcomings of previous visuzaliations in two ways. First, it retains the geogrpahic component of the data by plotting the data both on a traditional 2D plot as well as mapped to a geogrpahic map of the microhabiat cline. Thus recovering the geographic component. Second, and perhaps most importantly, all the graphs has been condenced into a single plot. Now the user can freely navigate the diversity estimates of all populations for the whole chromosome as well as for each Gene by simply navigating the visulization. Not only all information is contained in a single visualization. All estimates are escaled equally, which allows for easy comparisons. 

## This project

### Mapping of data to aesthetics

**Traditional Mapping**: The lower right corner of the vosualization will contain a traditional x/y plot showing sample name (x) and estimate (y). 

**Novel Mapping**: Estimates of diversity will be transformed to radial measures and plotted as circles on a map with the estimates of estandard error (SE) as a pulsating circle around the mean estimate (non-pulsating circle). Moreover, above the main visualization, the user will have access to a diagram of the full chromosome. All shown genes are interactive.

### Filtering

Data has been annonymized. The measures of SE are only shown in the pulsating visulization for minimalists purposes. 

### Extra ink

Background map and inset map are not generated from the data, however, they locate the data in a geographical scale, thus improving the delivery of the information. *i.e.* the concept of variation across a microhabitat cline is more clear when the geograohic cline itsefl id shown.

The measures of diversity are mapped to both the cirlces on the map and the bargraph on the lower left inset. This serves two purposes: One, reinforces the message. Two, provides a conrast of an old "clasical view" and a new view. The goal is to make it intituitive to the broadest audience possible.

### Motion

Transitions are used briefly. Text magnification is used when exploring the chromosome. The bulk of the motion is used in the pulsating circles that indicate the upper and lower bounds of the SE around the mean. 

### Perspective

Exposition: Popuations, overall number of genes and geographical locations are hard-coded. given the data.

Exploration: The user can chose which Gene to visualize each time.

## Assessmentces

Succeses: Defeinitely the bigger success of this visualizaion lies in the consolidation of multiple graphs into one single graph.

Limitations: It is unclear that the "geographical mapping of the estimates" is as clear as it could be. In some cases it has been considered gimmicky. 

Future Directions: Adding more genes, more chromosomes, more populations. Also, addition of other estimators such as Fst will enhance the power of the graph.

-jcbn


