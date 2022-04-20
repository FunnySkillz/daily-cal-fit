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
    * User can select/write what he had / will have for breakfast, lunch, dinner, etc.
    * Automatically sums up kcal, protein intake of the day
    * User can chose the MAX and MIN. calorie intake to fit his diet plan. 

* User can choose a preset diet plan (preset is created by personal trainer / bodybuilder [N. Jovanovic](https://www.instagram.com/nixazizu89/) )
    * losing weight
    * gaining weight
    * gaining muscle mass 

* User can copy a preset diet plan and then change the plan accordingly to fit his personal needs.

* User can take notes (his calorie intake of the day, recipe he took for breakfast, etc)
    * personal notes - what he likes, dislikes, any kind of text notes 

* User can view recipes
  * recipe displays ingredients
  * recipe displays approx. preparation time
  * recipe displays preparation steps
  * approx. kcal, protein amount, etc

* User can view details of every grocerie in the database
    * per 100g or per Unit (example: 1 Egg - 34g    )
    * kcal amount
    * protein amount
    * carbohydrates


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
