# BMIN5030 Final Project

This repository contains templates for the final written report and GitHub repository. Follow the instructions below to clone this repository, and then turn in your final project's code via a pull request to this repository.

1. To start, **fork** this BMIN503_Final_Project repository.
1. **Clone** the forked repository to your computer.
1. Modify the files provided, add your own, and **commit** changes to complete your final project.
1. **Push**/sync the changes up to your GitHub account.
1. Create a **pull request** on this, the original BMIN503_Final_Project, repository to turn in your final project.


Follow the instructions [here][forking] if you are unsure what the above steps mean.

DUE DATE FOR FINAL VERSION: 12/18/25 11:59PM EST. This is a hard deadline. Turn in whatever you have by this date.


<!-- Links -->
[forking]: https://guides.github.com/activities/forking/

Overview

Give a brief a description of your project and its goal(s), what data you are using to complete it, and what two faculty/staff in different fields you have spoken to about your project with a brief summary of what you learned from each person. Include a link to your final project GitHub repository.

The goal of my final project is to develop and evaluate predictive models for recovery from peripartum cardiomyopathy (PPCM). Using an EHR dataset from individuals diagnosed with PPCM, I hope to assess the variables most predictive of recovery and create and train models that can predict recovery for future cases using logistical regression and supervised machine learning techniques. After speaking with Dr. Arany and Dr. Yang, I gained access to a more complete dataset for PPCM than what I had originally planned to use, discussed what kind of questions may be most interesting to look at with this dataset, and we agreed that prediction models of recovery from ppcm would be novel and interesting to try to create and assess.

Introduction

Describe the problem addressed, its significance, and some background to motivate the problem. This should extend what is in the @sec-overview.

Explain why your problem is interdisciplinary, what fields can contribute to its understanding, and incorporate background related to what you learned from meeting with faculty/staff.

Peripartum cardiomyopathy (PPCM) affects approximately 1:1000 live births worldwide, is a significant cause of morbidity, and is in many places the leading cause of maternal peripartum mortality. To meet the diagnosis of PPCM, patients must have heart failure developing in the last month of pregnancy or within the months following delivery, left ventricular ejection fraction on echocardiogram below 45% and no other clinical reasoning behind the heart failure. The mechanism of PPCM is still being determined by researchers and clinicians. Retrospective studies have shown that 50-70% of patients with PPCM will recover (Jackson et. al 2024, Lewey et. al 2021). Studies investigating and developing prediction scores for PPCM have relied upon logistic regression methods (Jackson et. al 2024, Prameswari et. al 2024), but have not explored machine learning techniques. The goal of this project is to create and assess the efficacy of machine learning-based prediction models for recovery from PPCM, and compare to logistic regression methods.

This is an interdisciplinary question because it combines evaluation and comparison of data science techniques with understanding clinical data with real-world health implications. This could be useful for both assessing the utility of different predictive methods and for understanding what variables are important for treating and monitoring PPCM.
