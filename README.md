---
author: Bogdan Sebastijan
title: Daily-Cal-Fit
date: "2022-04-01"
---

# Daily-Cal-Fit Project

## Description of the initial situation

Calculating your approximate calorie intake is hard to keep track of. 
We have to use a search engine if we wish to know approx. amount of calories a product contains. 

## Current state

* Using a search engine to find every product one by one.
* Using a search engine to find recipes and filtering mostly by
ourselves which recipe would fit our diet plan.
* Taking notes on a paper/excel, etc.
* Hard to keep track and will result in losing interest in a week.

## Assignment

* Create an app that works both on IOS and Android. 

## Goal

* keeping track of your calorie intake is easy
* recipes are easy to keep track of
    * detailed preparation steps
    * approx. preparation time
    * approx. calorie intake, fat, carbs, etc.
* taking notes of your calorie intake is simple
* can set up a reminder
* Calendar view
* customizable for personal diet of choice

## Functional requirements

* User can create his own diet plan
* User can choose a preset diet plan
* User can take notes (his calorie intake of the day, recipe he took for breakfast, etc)
* User can view recipes
  * recipe displays approx. kcal amount
  * recipe displays approx. preparation time
  * recipe displays preparation steps
* User can view details of every grocerie in the database


## Not functional requirements

* Security
* Efficency
* Usability
* Portability
* Robustness
* Reliability

## Database 

* Through API from a reliable source [https://fdc.nal.usda.gov/]
* [Postgresql-db](https://www.postgresql.org/)

## Technology

* Intellij IDEA
    * Backend [Quarkus](https://quarkus.io/)
    * [Docker](https://www.docker.com/)
 * Frontend 
   * Flutter - Dart
