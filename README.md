# Course title: Data Analysis with R for Social Scientists

Level: Bachelor
Structure: 90 min per week, 14 sessions
Language: Englisch

Objective: 
1.	After this course, students will be able to write a BA-thesis involving basic empirical data analysis. 
2.	Expertise to apply regression analysis to large-N data

Prüfungsnebenleistung:
5 page report (no theory, no lit review) 

Modulprüfung:
Seminarpaper (Rmarkdown ~12 pages; incl. mini lit review, theory, further analysis)

Format:
Focus is on applied data analysis, sessions will involve basic introduction to main concepts and sessions where students directly apply data analysis techniques using real social science data.

Dataset: 

In-class: NBA Performance and Salaries (https://www.kaggle.com/datasets/thedevastator/exploring-nba-player-performance-and-salaries-19?select=salaries_1985to2018.csv)

Excersises/Report: Boston Housing Dataset


## Implementation: 

Jakob:	4, 5, 7, 8 + maybe DAG (before 4)

Jasper: 2, 10, 12, (1 / 14 ?)

WHK: 3, 6, 9, 11 + Prep, review, and layout gitbook


## Syllabus - by week of instruction
1. Intro to seminar
2. Exploratory data anaylsis (EDA)
  *	load data
  *	introduce WVS
  *	glimpse()
  *	skim()
  *	types of variables/ skalen
  *	univariate statistics (means, SDs, min, max)
  * ggplot
    *	histograms
    *	boxplots
    *	bar graphs
    *	Scatterplots
  * gtsummary
    *	Kreuztabellen
3. EDA - in class exercise
  *	Markdown intro
  *	With WVS/own data: Students apply EDA
4. Linear Regression - theory
  *	What is it?
  *	When and for what can it be used?
  * Formula (short)
  *	Assumptions (short)
  *	Interpretation of results
  *	Mediation (maybe theory into DAG session and example into application?)
  * Interactions?
  *	Multiple outcomes
5. Linear Regression – application
  *	Incl. Short theory and DAG
    *	application with WVS data
  *	interpretation of regression table in practice
  * Mediation
    * total + direct effect
  * maybe: regression diagnostics
6. Linear Regression - exercise
  *	With WVS/own data: Students apply Linear Regression
7. Logistic Regression - theory
  *	What is it?
  *	When and for what can it be used?
  * Formula (short)
  *	Assumptions (short)
  *	Interpretation of results
  *	Mediation? (not as easy to do right)
  *	Multiple outcomes
  * Multinomial
8. Logistic Regression - Application
  *	Incl. Short theory and DAG
    *	application with WVS data
  *	interpretation of regression table in practice
  * Mediation
    * total + direct effect
  * maybe: regression diagnostics
9.	Logistic Regression - Exercise
  *	With WVS/own data: Students apply Logistic Regression
10.	Prediction/ Margins – theory and application
  *	predicted probabilities (at various covariate levels)
  *	marginal effects
11.	Prediction/ Margins – exercise 
  *	With WVS/own data: Students apply Logistic Regression
    * Predict for Linear + Logistic Regressions from previous excercises 
12.	Reporting/ Visualization
  *	formatted regression tables
  *	Publication-ready formatting/ labelling of visuals
  *	coefficient plots
13.	Discussion of ideas for term papers
14.	Outlook
  *	Machine learning


Idea (Jakob): Maybe we can combine 13+14 (14 doesn't have to be that long?) and
make room for a DAG session before starting out with Linear Regression. I think
that if we do want to include DAGs (I want to), we should give the ideas some
space. Some DAG theory and examples and then we can start out with linear reg
and use DAGs throughout

* DAG session ideas
  * Correlation does not equal Causation/Identification of effect(s) of interest
  * DAGs in principle
    * Indirect causal effect/Overcontrol Bias/Pipe
    * Confounders/Fork
    * Colliders
  * Total/Direct effect
    * Identification
  * dagitty.net
  