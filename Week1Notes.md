# Reproducible-Research

- reproducible research - important that we communicate our research in a way so that someone else can reconstruct it
- make analytic data and code available so that others may reproduce findings

##How to document your research?

Issues from reproducibility:

- no agreed upon notation system for communicating data anylsis, everyone does it differently (words, computer code...)


##Concepts and ideas
- replication of findings: standard for strengthening scientific evidence
- issues: some studies cannot be replicated because studies are getting bigger and bigger (lot of money involved, no time because it is too big, some studies are unique)

##Why reproducible research?
- computational methods and data has to be made available
- serves as validation of data analysis
- what is driving reproducible research - technologies that allow us to collect data -> complex and high dimensional data sets, computing power increases and allows for more sophisticated analyses

##What do we need for reproducible research?
- analytic data - not raw data because we anyway use a subset of raw data
- analytic code applied over analytic data
- documentation of code and data 
- standard means of distribution - how to access this data

###Challenges
- considerable effort
- download data/results individually
- readers may not have the same resources as original authors
- few tools to help readers/authors - it is growing

##Literate statistical programming
- article is a stream of text and code  
- analysis code is divided into text and code chunks
- presentation code formats data results (forms of tables, figures)
- literare programming requires a documentation language (human readable) and a programming language (machine readable)
- Sweave - uses Latex and R as the documentation and programming languages
 - limitations to Sweave - focuses on LaTex - markup language, not frequently updated...
- alternative is knitr package for R - Latex, Markdown, HTML

#Structure of a data analysis
- define question
- define data set
- determine what you can access
- obtain data
- clean data
- exploratory data analysis
- statistical prediction/modeling
- interpret results
- challenge results
- synthesize results
- create reproducible code

##Define a question
- to remove variables that are not in scope of the study
- narrow down questions to as specific as possible
- remove noise in advance
- used to simplify a problem

##Define data set
- depends on my goal:
	- descriptive - a whole population
	- exploratory - a random sample with many variables measured
        - inferential - the right population, randomly sampled
        - predictive - a training and test data set from the same population
        - causal - data from a randomized study
        - mechanistic - data about all components of the system

##Determine what data can you access
- free on web
- buy data
- respect terms of use
- if data does not exist, then you need to generate it yourself

##Obtain the data
- raw data
- reference the source

##Clean the data
- understand how data was pre-processed
- what is the source of data?
- may need to be reformatted
- determine if data is good enough

##Exploratory data analysis
- looks summaries of data
- what does it look like - relationships between the data, format, any missing data
- exploratory analysis (clustering)

##Statistical prediction/modeling
- exact methods depend on the questions of interest
- measures of uncertainty

##Interpret results
- use appropriate language: "describes", "correlates", "leads to", "predicts"
- give an explanation
- interpret coefficients
- interpret measures of uncertainty

##Challenge results
- challenge all steps: questions, data source, processing, analysis, conclusions, measures of uncertainty, choices of terms to include in models
- think of potential alternative analyses

##Synthesize results
- lead with the question
- summarizes analysis
- don't include every analysis
- include pretty figures

##Create reproducible code
- using knitr

##Organizing data analysis
- no universal way
- files: data (raw data, processed data should be tidy), figures (exploratory and final), R code (raw unused scripts, final scripts, R markdown files), text (readme, text of analysis and report)




