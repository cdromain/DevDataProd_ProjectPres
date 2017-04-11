<style>

/* slide titles */
.reveal h3 { 
  font-size: 45px; ##60px
  color: black;
}

/* heading for slides with two hashes ## */
.reveal .slides section .slideContent h2 {
   font-size: 35px; ##40px
   font-weight: bold;
   color: #25679E;
}

/* ordered and unordered list styles */
.reveal ul {
    font-size: 25px; ##50px
    list-style-type: square;
}

.reveal ol {
    font-size: 25px; ##50px
}

.reveal p {
    font-size: 25px; ##50px
    color: red;
    list-style-type: square;
}


.reveal strong {
  #color: #25679E;
  color : black;
}

.reveal pre code {
  display: block; padding: 0.5em;
  font-size: 0.8em;
  line-height: 1.1em;
  background-color: white;
  overflow: visible;
  max-height: none;
  word-wrap: normal;
}

.reveal code {
  font-size: 1em;
  background-color: #f8f8f8;
  color : #b11d42;
}

.section .reveal h1 {
   font-size: 1.5em;
   line-height: 1.5em;     
}

.section .reveal p {
   font-size: 0.7em;
   line-height: 1.5em;     
}

.section .reveal .state-background {
   background: #25679E;
}

.reveal .controls div.navigate-left,
.reveal .controls div.navigate-left.enabled {
  border-right-color: #a9d4f8;
}

.reveal .controls div.navigate-right,
.reveal .controls div.navigate-right.enabled {
  border-left-color: #a9d4f8;
}

</style>

Developing Data Products course project : Prediction Playground
========================================================
author: Romain Faure
date: April 2017


A PEDAGOGICAL PROJECT
========================================================

## Introducing *Prediction Playground*

Started from the wish to be able to actually *play* with **machine learning** concepts and models in an interactive manner in order to develop understanding and intuition - hence the idea of a *"playground"*.     

The idea is to be able to quickly apply different models to different data sets, using different predictors and compare the resulting outputs.

Link to the app : https://cdromain.shinyapps.io/prediction_playground/

## A triple pedagogical purpose

1. This project allowed me to learn how to develop a web application using [Shiny](https://shiny.rstudio.com/) reactive framework in RStudio.</small>

2. Developing the app gave me an opportunity to learn more about **machine learning** concepts and models.

3. *Playing* with the app enabled me to deepen my understanding and intuitions regarding machine learning concepts (which was the initial goal) - hopefully, the app will benefit others in the same way.

DATA SELECTION AND MODEL BUILDING
========================================================

## Data selection

## Model building

## Included help
- Application functionalities.
- Data sets.

RESULTS AND MODEL EVALUATION
========================================================

## Numerical output

## Plot


```r
plot(cars)
```

<img src="index-figure/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="200" height="200" />

*INCLUDE AND SHOW R CALCULATION code as an example*

CREDITS
========================================================

- This HTML5 presentation was created in RStudio version 1.0.136 (R version 3.3.3, OSX 10.11.6) using the [R Presentation](https://support.rstudio.com/hc/en-us/articles/200486468-Authoring-R-Presentations) format with custom CSS (added inside the `.Rpres` file, available on the presentation [GitHub repo](https://github.com/cdromain/DevDataProd_ProjectPres)).

- This reproducible pitch presentation was produced for the *Developing Data Products* course project, part of the Johns Hopkins Data Science Specialization on [Coursera](http://coursera.org/).