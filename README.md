<p align="center">Organized by CONTAIN-LATAM-UK PROJECT</p>
<p align="center">International multidisciplinary project funded by the Newton Fund Latin American Biodiversity</p>

# Statistical methods for informing the management of contracting or range-expanding species

A large number of highly damaging invasive non-native species (INNS) have become established in South America. They affect livelihoods and ecosystems, and contribute to the decline of native species.
In those areas where taking no action is not acceptable, cost-effective management of these populations must consider by how much should INNS density be reduced, and how.
This depends on the resources available, on the relationship between the abundance of the focal INNS and its impacts, on which categories of individuals in a population contribute most to spread, and on how environment interacts with demography.

Addressing these questions requires models to make sense of data, to estimate key demographic parameters, to make predictions of population response to alternative management scenarios, and finally to evaluate agreement between observed management outcomes and original predictions, in order to update the management model.

CONTAIN is an international multidisciplinary project funded by the Newton Fund Latin American Biodiversity Programme Phase II: Biodiversity – ecosystem services for sustainable development. Our team includes The University of Aberdeen and Queen’s University Belfast and 9 research groups from Argentina, Chile and Brasil (CONICYT, CONICET, FAPESP, Vida Silvestre). We aims at providing the evidence and tools required for addressing the challenges posed by INNS in Latin America. 

**As part of the CONTAIN project we have set up a training programme in three parts, to disseminate useful statistical population modelling approaches for informing the conservation or management of species with distributions that are changing in space and time. We have a few spaces available on these courses, which we are keen to open to other biologists in Latin America who work on similar issues.**

**Part 1** will build on the regression framework to analyse survey data (counts or presence/absence), in order to describe changes in occurrence in space and time, and to identify its potential environmental or endogenous drivers (e.g. habitat or dispersal limitation). **Part 2** will introduce Bayesian inference, a flexible framework which is particularly suitable for modelling complex ecological systems, enabling the combination of data from multiple sources, the propagation of uncertainty and more generally, the formulation of descriptive or process-based models that can be tailored to particular data sets and questions. 
**Part 3** will used the Bayesian approach to introduce Integrated Population Models, as a tool to investigate the processes underlying population dynamics, estimate parameters, and inform the adaptive management of populations.


## Part 1: Statistical modelling of presence-absence and count data in space and time.
**02/05/2019 to 04/05/2019 (3 days), Buenos Aires, Argentina**

### Context & Aims
The first part of this course will cover models aimed at estimating population variation in space and time, from structured or opportunistic survey data. These models may be used to monitor changes in distribution, diagnose the causes of change, and to parameterize process-based models (such as Range-Shifter).
We will explore a range of modelling strategies that enable the use of such models for different purposes, from simply describing spatio-temporal variation using structured and unstructured random effects, to investigating the environmental drivers of animal and plant distribution, for example based on resource selection functions. 

### Course format 
* research seminars, illustrating the context in which the tools may be applied (including an application of the Range Shifter individual-based modelling platform),
* short introductions to the theory underlying the statistical methods, 
* ample hands-on practice with real data, in R.

### Topics
* Generalized Linear Models for presence/absence and count data
* Accounting for survey effort
* Clusters
* Generalized additive models: capturing non-linear change with smoothing splines
* Models for structured errors
* Temporal correlation
* Spatial correlation

* Combining different structures in one model: which and why.

### Prerequisites
The course assumes familiarity with the theory and practice of linear modelling (regression) framework, as well as familiarity with the use of the R statistical software and programming language. We will provide a *very* brief recapitulation of linear modelling at the beginning of the course, but will be unable to provide a full introduction to the topic.
We will provide links to introductory material on linear modelling and R, should participants wish to update their skills in preparation for the course.
Complete R code will be provided for all the practical workshops, and teaching assistants will be available to support the participants.

### Software
You will need a recent (preferably the latest) version of R on your computer, including the following additional packages:
- rgdal
- rgeos
- sp
- tmap
- viridis
- shiny
- shinythemes
- RColorBrewer
- RCurl
- gamm4

## Parts 2 & 3: Introduction to Bayesian modelling and Bayesian modelling for population ecology
**2 + 5 days (with a weekend break), December 2019, Bariloche, Argentina**

Parts 2 and 3 can be taken as a follow-up to part 1, or as a standalone course. 

Guests from outside the LATAM-CONTAIN project must take parts 2 & 3 together.

Participants of all countries will get to know each other through evening events, two half-day breaks and if they wish to, during the weekend break. Poster & drinks sessions will facilitate exchanges about our respective research interests.

## Part 2: Introduction to Bayesian modelling
**5-6th December 2019 Bariloche, Argentina**

### Context & Aims
The second part of this course will introduce the Bayesian modelling framework, with linear and hierarchical modelling applications. We will provide an intuitive introduction to the basic theory and methods, illustrated by research seminars, practical activities and applications with real data.
The course will introduce you to techniques like MCMC estimation using the BUGS language, and to the idea of incorporating expert knowledge in the analysis through the use of Bayesian priors. 
We will illustrate these concepts using some of the models covered in part 1. This part of the course will provide you with the foundations for understanding the important and growing part of modern ecological modelling literature which employs Bayesian approaches, and will enable you to move on to more advanced population models (Course part 3). 

### Course format 
* research seminars, illustrating the context in which the tools may be applied, 
* short introductions to the theory underlying the statistical methods, 
* ample hands-on practice with real data, in R.

### Topics
* Bayes rule
* Bayesian modelling, priors and likelihood
* Markov Chain Monte-Carlo estimation with rJAGS
* Bayesian analysis of GLM and hierarchical models

### Prerequisites
As for Course part 1, plus familiarity with the theory and practice of generalized linear and multilevel (random effect) modelling. Complete R and BUGS code will be provided for all the practical workshops, and teaching assistants will be available to support the participants.

### Software
You will need a recent (preferably the latest) version of R and JAGS on your computer, including the following additional packages:
- rgdal
- viridis
- shiny
- shinythemes
- RColorBrewer
- RCurl
- gamm4
- rjags

For instructions on downloading JAGS, see the home page at http://mcmc-jags.sourceforge.net.

## Part 3: Introduction to Integrated Population Models 
**5-6th December 2019 Bariloche, Argentina**

### Context & Aims
The third part of the course will expand on part 2, and make use of the Bayesian modelling framework to fit population dynamics models. We will first explore several approaches for estimating demographic parameters from different types of data and observation processes, such as occupancy or capture-recapture data. We will then see how the different sources of information on demography may be combined into integrated population models (IPMs), in order to gain a better understanding of the population dynamics, to obtain more precise estimates of demographic parameters and their variation over time, space or life history stages. This part of the course will be essentially applied, illustrated by research seminars and applications with data.

### Course format 
research seminars, illustrating the context in which the tools may be applied, 
short introductions to the theory underlying the statistical methods, 
ample hands-on practice with real data, in R.

### Topics
* Models for observation error and missing data
* Occupancy models
* Mark-recapture models
* Integrated population models (IPMs)

### Prerequisites
This part of the course requires prior attendance to part 2, or equivalent experience. Complete R and BUGS code will be provided for all the practical workshops, and teaching assistants will be available to support the participants.


