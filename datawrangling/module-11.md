---
layout: tutorial
title: Module 11
permalink: /module-11
---

Much of this module will be spent going through an interactive tutorial that will teach you some foundational analytic techniques. I have built an R package that provides a structured, interactive environment and the following instructions will get your computer set up to run these tutorials:

1. Make sure the version of R on your computer is v3.4.0 (2017-04-21) or greater
2. Make sure the version of RStudio is v1.0.143 or greater
3. Install the devtools packackage with `install.packages("devtools")`
4. Run `devtools::install_github("bradleyboehmke/learningAnalytics")`
5. Activate the first tutorial with `learningAnalytics::get_tutorial("hello")`

Walk through this first tutorial. If it appears to function appropriately, fantastic! If not, please get in touch so we can try resolve your issues. Thanks and I look forward to class!

If you get through the "hello" tutorial and want to get going on the next tutorials before class, you can activate the next tutorial with `learningAnalytics::get_tutorial("EDA")`

Then on Friday you will enjoy another "hackathon" where your group will import a real life customer data set and perform some analyses.

<hr>

## Class Prep

Download the following material for class: &nbsp; <a href="https://www.dropbox.com/sh/qdyugd04010eufc/AACzZFwmnGGdZZ78oV9DWz-aa?dl=1" style="color:black;"><i class="fa fa-cloud-download" style="font-size:1em"></i></a>

<hr>

## Continued Learning

To continue learning analytic techniques outside of class, check out the following interactive tutorials:

- `learningAnalytics::get_tutorial("Unsupervised")`:  Principal Components Analysis & Cluster Analysis
- `learningAnalytics::get_tutorial("Linear Regression")`: Linear Regression
- `learningAnalytics::get_tutorial("Supervised Classification")`: Logistic Regression & Discriminant Analysis
- `learningAnalytics::get_tutorial("Resampling")`: Leave-One-Out Cross-Validation, k-Fold Cross Validation, & Bootstrapping
- `learningAnalytics::get_tutorial("UModel Selection")`: Best Subset & Stepwise Selection for Linear Models
