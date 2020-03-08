---
title: 'L01 General Introduction: Making Sure Everything Works'
categories: [lessons]
tags: [intro, r, rstudio]
---

## Goals:

* Install R and R Studio and start working with them
	* R <https://www.r-project.org/> 
	* R Studio <https://www.rstudio.com/>
* Get to know R Notebooks (R markdown)
* Start learning R with the `swirl` package
	* Beginner: *R Programming: The basics of programming in R*
	* Intermediate: *Getting and Cleaning Data* 

## Software:

* R <https://www.r-project.org/> 
* R Studio <https://www.rstudio.com/>

## Class, Part I

* R Studio Interface
* Installing libraries (packages)
* R Notebook elements: combining prose and code
* Converting R Notebook into different formats

### Installing `rmarkdown`

Instructions here: <https://bookdown.org/yihui/rmarkdown/installation.html>

### YAML header

``` r
---
title: "R Notebook Test"
output:
  html_document:
    df_print: paged
    toc: true
---
```

You can download the notebook file from [here](https://univie-histr-2019.github.io/files/01/rNotebook_Test.Rmd.zip), but it is better if you try to build your own peice by piece, regenerating the notebook with every new element added.

**NB:** More information on R Markdown:

* <https://rmarkdown.rstudio.com/lesson-1.html>
* <https://bookdown.org/yihui/rmarkdown/> 

## Class, Part II

1. Install `swirl`:

``` r
install.packages("swirl")
```

2. Run a course by typing the following in your command line (might be better to use your command line, instead of R Studio). Type `r` to start R, then:

``` r
library(swirl)
install_course("R Programming E")
swirl()
```

3. Complete "R Programming E" course. There should be an option to send an email to the instructor, confirming that you have completed it.

**NB:** More information on the `swirl` library: <https://github.com/swirldev/swirl_courses>

## Reference materials:

* Your `R` installation may ‘speak’ your main language. It is nice on one hand, but can be quite inconvenient in class, where the main language is English. You may have to do cast some spells to switch `R` into English. Possible solutions can be found here: <https://stackoverflow.com/questions/13575180/how-to-change-language-settings-in-r/>

## Homework:

* Complete swirl's course *R Programming: The basics of programming in R*
* Write a report (R Notebook), summarizing what you have learned. Use one or two examples from each lesson.

## Submitting homework:

* Homework assignment must be submitted by the beginning of the next class;
* Email your homework to the instructor as attachments.
	*  In the subject of your email, please, add the following: `070184-LXX-HW-YourLastName-YourMatriculationNumber`, where `LXX` is the numnber of the lesson for which you submit homework; `YourLastName` is your last name; and `YourMatriculationNumber` is your matriculation number.