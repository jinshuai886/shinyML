## New minor version of shinyML package
This is a new minor version (0.2.0) of the shinyML package. 
In this new version I have:

* Added three new tabs **Compare models performances**, **Feature importance** and **Table of results** at the top of dashboards to explore input dataset before running the models 

* Added two valueboxes on the left of the dashboard to indicate memory cluster size and number of used CPU(s). 

* Fixed an issue on "Link" parameter of **Generalized linear regression** model: this parameter was not taken into account by the model

* Fixed an issue on user interface on **Generalized linear regression** box: the cursor was not at the right position when selected

* Removed x parameter on `shiny_h2o` and `shiny_spark` functions to make it run even more easily. 

## Resubmission
This is a resubmission. In this version I have:

* Rewrote CRAN URL in canonical form (https://CRAN.R-project.org/package=shinyML) on Readme.Rmd file


## New patch version of shinyML package
This is a new patch version (0.1.1) of the shinyML package (I've fixed bugs without adding any significant new features). 
In this version I have:

* Added a missing block to shiny_h2o.R to make autoML method working 

* Default 'share_app' argument of `shiny_h2o` and `shiny_spark` examples have been set to FALSE


## Resubmission
This is a resubmission. In this version I have:

* Capitalized only the first letter of names instead of the whole name in the DESCRIPTION file 

* Rewrote all descritption field on the DESCRIPTION file to make it clearer: please notice that the package is just an implemnetation of a shiny app 


## Resubmission
This is a resubmission. In this version I have:

* Modified the title to make it describe the package more precisely

* Checked the new title lenght remains less than 65 characters.

* Modified the title in the Readme.Rmd file to make it correspond to the title in the DESCRIPTION file  

* Written "License: GPL-3" instead of "GPL-3 | file LICENSE" in the DESCRIPTION file

* Added a reference in the description field on the DESCRIPTION file in the form "authors (year, ISBN:...)" that describe the methods in the package 


## Resubmission
This is a resubmission. In this version I have:

* Converted the DESCRIPTION title to title case.

* Right spelled words in DESCRIPTION:
    differents (9:111) -> different
    serie (9:145) -> series
    shareable (8:66) -> this word has been deleted 
    
* Prevented the Description field to start with the package name 

## Test environments
* OS X (on travis-ci), R-oldrel, R-release
* linux (on travis-ci), R-oldrel, R-release
* win-builder (devel and release)

## R CMD check results
There were no ERRORs, WARNINGs or NOTEs

## Downstream dependencies
There are currently no downstream dependencies for this package