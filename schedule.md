Class Schedules (Spring 2014)
-------
**Statistical Modeling and Data Visualization  (PUBHLTH 690NR)**   
**Taught by [Nicholas Reich](http://people.umass.edu/nick), UMass Biostatistics**

_Shortcuts to classes_

January   [21](#c1)  [23](#c2)  [28](#c3)  [30](#c4) <br>
February  [4](#c5)  [6](#c6)  [11](#c7)  [13](#c8) [20](#c9)  [25](#c10)  [27](#c11)


<a name="c1"/>
#### Class 1 (Jan 21): Course Introduction
_Activities_
* quiz: wits and wagers
* syllabus go-through, GitHub introduction
* in-class computer discussion
* class discussion: look at visualizations 
* Small group discussions
  * principles of effective data visualization
  * how to best collect W&W data
* Big group discussion/wrap-up

_Homework_
* Problem Set 1: Due Thursday, 2/13/2014 (by the beginning of class)
* Create GitHub account, pull course repo into a directory on your machine. For instructions, see [this video](http://www.youtube.com/watch?v=YxZ8J2rqhEM).
* Read through the syllabus
* Take [CAOS test](https://apps3.cehd.umn.edu/artist/user/scale_select.html)

<a name="c2"/>
#### Class 2 (Jan 23): Introduction to Regression
_Activies_
* introduction to ggplot2 (15 min)
* small groups: establish 5 specific criteria for creating good data visualizations (10 min)
* big group: consensus criteria (15 min)
* mini-lecture: introduction to regression (30 min)

_Homework_
* Problem Set 1: Due Thursday, 2/13/2014 (by the beginning of class)
* Create a short reproducible document (using knitr) that describes the basic structure of a dataset and summarizes some key features of the data using a few key tables and figures. Choose a dataset from [these datasets](http://biostat.mc.vanderbilt.edu/wiki/Main/DataSets) or the ones in the class Google Drive. If your dataset has a lot of variables, focus on a subset of them -- less than 6 or so -- for the purposes of this exercise. Your write-up should answer the following questions:
  * What is the background/context for this data? 
  * How many observations are there?
  * What is the unit of observation?
  * Is there any missing data? If so, are there patterns to the missingness?
  * What are the key variables and what do their distributions look like?
  * Is there a pair of variables that might work well for a Simple Linear Regression? (You don't necessarily need to run one, but you could.)
  * Are there any obvious outliers in the data?

<a name="c3"/>
#### Class 3 (Jan 28): Geometry of regression and least squares
_Activities_
* homework discussion/questions (10 min)
* warm-ups (10 min)
* mini-lecture: least squares and geometry of regression (30 min)
* lab: OpenIntro Lab 7. (20 min)
* exercise: Everyone make a guess at minimal RSS after three tries with the plot_ss(). Take averages in groups. Compare to minimal RSS based on summary(lm()) output.

_Homework_
* Problem Set 1: Due Thursday, 2/13/2014 (by the beginning of class)
* Add one or two simple linear regressions to your dataset write-up. 
* Finish OpenIntro Lab 7.
* Install the HSAUR2 package, read up on and explore the BtheB dataset (hint: ``?BtheB''). Be prepared to describe the dataset and answer questions about it in next class. 

<a name="c4"/>
#### Class 4 (Jan 30): Hands-on SLR practice 
_Activities_
* warm-ups (10 min)
* introductions (5 min)
* OpenIntro lab 7 questions (5 min)
* More dataset descriptions/results, including BtheB (5 min)
* small groups: Formulate and fit a reasonable SLR model to BtheB dataset. (30 min)
* whole class: Present regressions. Talk about different model formulations and results. (15 min)

_Homework_
* Problem Set 1: Due Thursday, 2/13/2014 (by the beginning of class)
* In your small groups, create a write-up for a simple analysis of the BtheB dataset. Each group should create a repository on GitHub for their analysis. The .Rnw or .Rmd file that you use should be in that repository and every member of the group should have at least one commit or push to the repository before the next class. (You should not commit any additional files, like the .aux files from LaTeX compiling, just the files that are needed to comile your analysis.) Here is a minimal list of things that should be included in your write-up. I encourage you to push beyond just this list, however. 
  * A few sentences of background/context for the BtheB dataset.
  * A quantitative and/or visual description of what variables you chose to use for your analysis, along with a hypothesis (or two) that you will be testing.
  * A description of the characteristics of the missing data (including a figure if needed) and a statement and justification as to whether your group is concerned about the missingness having an impact on your analysis.
  * Results, with interpretation, of output from an SLR model. We haven't discussed yet using binary predictors or X variables, but feel free to include them. The interpretation is very similar. "For a one unit change in X, ..."
* Read [this description](http://nicercode.github.io/guides/functions/) of how to write and use functions in R.

<a name="c5"/>
#### Class 5 (Feb 4): R^2, ANOVA
_Activities_
* warm-ups (10 min)
* lecture: SLR final concepts (40 min)
* writing functions in R (15 min)

_Homework_
* Problem Set 1: Due Thursday, 2/13/2014 (by the beginning of class)
* Create a "slr()" R function that takes x and y vectors and outputs a list with two objects: (1) a fitted lm() object and (2) by-hand betas (calculated by likelihood or formulae). Try to write this as a function, but if you have trouble, then just write it as a few lines of R code and create an object as described.
* Use this new slr() function/code to refit the SLR models in your dataset writeup. Compare the results and make sure they are returning the same thing. 

<a name="c6"/>
#### Class 6 (Feb 6): 
_Activities_
* warm ups (15 min)
* demo: GitHub and RStudio demo (10 min)
* small groups: compare slr() functions from homework. summarize similarities and differences in approaches. Was there a consensus "best" approach? (20 min)
* lecture: interpreting coefficients from MLR.

_Homework_
* Problem Set 1: Due Thursday, 2/13/2014 (by the beginning of class)

<a name="c7"/>
#### Class 7 (Feb 11): 
_Activities_
* warm ups: wits and wagers (15 min)
* small groups: collecting data on wits and wagers (10 min)
* homework update
* MLR coefficient interpretation and matrix notation (20 min)
* MLR example walk-through (15 min)

_Homework_
* Problem Set 1: Due __Tuesday, 2/25/2014__ (by the beginning of class)
* Add a fitted MLR to your dataset write-up. State the model, in equation form. Describe it in words. Interpret your fitted coefficients.

<a name="c8"/>
#### Class 8 (Feb 13): 
SNOW DAY, CLASS CANCELLED.

<a name="c9"/>
#### Class 9 (Feb 20): 
_Activities_
* lecture: matrix formulation of MLR

_Homework_
* Problem Set 1: Due __Tuesday, 2/25/2014__ (by the beginning of class)

<a name="c10"/>
#### Class 10 (Feb 25): 
_Activities_
* wits and wagers CI exercise

_Homework_
* Problem Set 1: Due TODAY at beginning of class


<a name="c11"/>
#### Class 11 (Feb 27): 
_Activities_
~ Mid-semester course evaluations (25 min)

_Homework_
