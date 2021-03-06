---
author: Mark Gingrass
categories:
- Career
- government
- Tools
date: "2019-01-17"
slug: job-roles-what-do-i-actually-do
tags:
- data science
title: Job Roles - What do I actually do?
---
<p align = "center" style="border:7px solid black; padding: 10px; border-left: 30px solid blue;border-left-color: blue;font-size:1.5em">My name is Mark and I am an Operations Research Analyst!</p>

This article is an overview of the roles an ORA is may perform within this my organization.

# Operations Researcher

> What do you do for work?

I will explain my daily role as an **Operations Research Analyst** working for the FDA in the Center for Tobacco Products Office of Science in the following sections of this article.

In general, as an operations research analyst requires me to do quantitative research to improve business practices. This sometimes involves data mining, optimization, statistical analysis and modeling.

I take ownership of data from the "cradle to the grave." That is, I am responsible for taking raw data and turning it into business insights using the Extraction, Transformation and Loading (ETL) process similar to the graphic below.

<p align="center"><img src="/img/etl_process.PNG" width="65%"></p>

I help determine the future data architectures required to handle processing and transforming of the incoming "big" data that is expected. That is, to better align present business practices for greater success tomorrow.

I will dive deeper into the specifics of my current roles in a context most should understand in the following sections. This list is not exhaustive and changes frequently.

## Data Modeling

I help establish a one to one correspondence between items in the real world and the data tracking using Logical Data Models and Physical Data Models. The goal is to track the life cycle and workflows of submissions and documents.

I advise and quality control the representations of the submissions. For example, a **submission** may have a **receipt date**, **submission counter**, and a **point of contact**. I also quality control the relational model in Oracle Data Modeler.

There are numerous scenarios to think about while developing models:

*  Industry submits a duplicate information with varying quanities
*  How to define a *product*
*  Define a *co-packaged* product
*  Define an Ingredient vs a Complex Ingredient
*  Is *part* the same thing as *component*
*  How to deal with multiple configurations of same product
*  Structuring or *indenture* chain of products
*  Establishing a single source of truth for data
*  How to share data with other organizations

There are countless more complications to work through over time. One thing to focus on is the potential questions we want to answer in the future. Examples such as:

*  What **products** contain more than xx mg of **Ingredient** A
*  Show me all of the **component** parts of **product** B and the history
*  Find all **products** with this **characteristic**
*  What is the general trend for the makeup of products across the industry

Ultimately, the system should be designed in such a way to make answering scientific questions more efficient.

## Workflow Requirments

I help upgrade our information systems to better support submission processing. I help facilitate the requirements required to migrate from legacy systems to modern systems. The system handles a small piece of a larger scale project. Specifically, it allows Program Managers (PMs) to assign, track, and edit workflows for scientists and administrators.

When a new or modified product enters the market, the PM will determine which scientists are required to review the product. This could be as many as a dozen disciplines. The system helps track this process and enable users to research content from disparate sources improving efficiency and effectiveness of review activities.

This is more of an aesthetics role or a Human Integration Role. I determine if the interface is usable for the PMs to perform their roles more efficiently. This can include things like adding drop down menus, required fields, radio buttons, search bars, etc. Understanding the capabilities of the underlying technology and the end user needs is crucial.

This project uses the [SPRINT](https://yodiz.com/help/what-is-sprint/) methodology, with specific tasks to be completed and reviewed iteratively. The cadence is usually once every two weeks. Jira, a tool used to track progress is widely used to track issues and performance of the project.

I also help set the exit (or acceptance) criteria for the tasks. The goal is to avoid malformed or unknown requirements for the contractors and instead, gather true requirements for the contractors to take action on.

## Ingredients

Submitted ingredient applications contain names that may include a combination of scientific names, brand names, common
names, abbreviations, descriptions, manufacturer codes, substance registry codes, etc. They may contain incorrect punctuation, spelling errors, hyphenation, or incorrect word ordering.

A single manufacturer may use many names for the same ingredient over time or across products. Manufacturers may differ from each other in the way they name the same substance.

These qualities have serious consequences in regulation. They deter a reviewer or researcher from unambiguously identifying an ingredient.

I am part of the *Ingredient* standardization committee. I help create unambiguous methods of naming ingredients. Part of this process starts with using the [International Union of Pure and Applied Chemistry](https://www.siyavula.com/read/science/grade-12/organic-molecules/04-organic-molecules-03){target="_blank"} (IUPAC) standard naming conventions.

<p align="center"><img src="/img/iupac.PNG" width="65%"></p>

I used 'R' to help curate the verbatim reported chemical names and explore some of the issues with the current data e.g.:

*  duplication
*  misspellings
*  ordering
*  removing extra symbols and punctuation
 
I also created a dynamic look-up table for the Science Adviser and contractors to make research more efficient for them. Finally, I am exploring the use of *ontology* software such as [protege](https://protege.stanford.edu/){target="_blank"} to help organize the various uses of chemical data.

I am also a contributing member of the future Ontology Governance Subgroup.

## Migration

My role is to create "stories" and generate requirements for contractors to migrate from an Access database to a modern database system with user interaces.

## SAP/HANA Reporting

I work with contractors developing reporting metrics as *dashboards*.

Some of the generated reports include:

*  Review progress
*  Real time performance reports
*  Monthly closed reports
*  Monthly opened reports
*  Unresolved reports

The goal is to establish more robust requirements to allow more flexibility in the reports - such as the ability to drill down to detailed levels from an aggravated view. I aim to promote awareness of these reports to the end users. Ultimately, the reports should be capable of flagging anomalies and investigate the causes. Even further, detection of possible future issues (predictive analytics).

## Exploratory Data Analysis

I perform exploratory data analytics on all of our data using R and Python. This is a good way to find quality issues and to measure trends and view ad hoc metrics. 

## Ingest Modeling

An over arching process that encompasses the holistic view of the entire organiation. I refer to as "Ingest Modeling". Our team is trying to map the entire process our organization performs, from cradle to grave. We are mapping this process for a couple of reasons:

1.  It hasn't been mapped before
2.  If you don't know where you are, you can't get to where you want to go
3.  We can now get metrics for the processes
4.  Find duplication across Offices and find an Enterprise solution for all stakeholders

## Events

I keep up with emerging technologies by attending events such as Government Advances in Statistical Programming (GASP), CoLab and Gartner.

## Learn/Teach

*  Law
*  COR Training
*  Develop Tutorials
*  Learn Back End databases

#### COR I Certification

*  No previous experience is needed.
*  Functional Experience Transcript is not required.
*  A minimum of 24 CLP hours is needed.

You will need to complete the following trainings for your CLP hours:

*  8 hours COR Training
*  16 hours of Appropriations Law