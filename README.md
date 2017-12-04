# Introduction to Big Data

## What launched the Big Data era?

* Data Science #1 catalyst for economical growth
* Big Data is a stream of data
* Cloud Computing = Computing on demand = dyanmic and scalable data analysis

## Applications: What makes big data valuable

* Big Data -> Better Models -> Higher Precision
* Big Data has enabled personalized marketing
* Big Data has enabled personalized healthcare

## Where Does Big Data Come From?

* Machines
* People
* Organizations

<p align="center">
  <img src="https://www.i-scoop.eu/wp-content/uploads/2016/07/The-traditional-data-information-knowledge-wisdom-pyramid-source-Mushon.gif" />
</p>

* Interactive visualization: http://lod-cloud.net/versions/2017-08-22/lod.svg

## Machine-Generated Data: It's Everywhere and There's a Lot!

* Largest source of data
* Internet of Things
* Real time problem detection
  1. Customer Relations
  2. Fraud Detection
  3. System monitoring / control
* SCADA (Supervisory Control and Data Acquisition)

## Big Data Generated By People: The Unstructured Challenge

* Unstructured data
* Huge growth in data

|Company|Data Processed Daily|
|----|:----:|
|eBay|100PB|
|Google|100PB|
|Facebook|30PB|
|Twitter|100TB|
|Spotify|64TB|

### Hadoop

* Handle big batches of distributed information

### Spark / Apache Storm

* Real time processing
* Integrate with any database or store technology

### Data Warehouse

* Datasource integration to one place
* Data gets extracted from different datasources and transformed and loaded in central database. This is called ETL
* Used for structured data
* Doesn't fit well with today's dynamic data world


<p align="center">
  <img src="https://i.imgur.com/Q1m7wPL.jpg" />
</p>

## Big Data pipeline

<p align="center">
  <img src="https://i.imgur.com/zmNm4xj.jpg" />
</p>

## Organization-Generated Data: Structured but often siloed

* Highly structured data
* Data Silos (no 1 silo has access to all information)

* Commercial Transaction
  1. **Detect correlated products**
  2. **Estimate demand**
  3. Capture Fraudulent Activity  
* Banking / Stock records
* Credit Cards
* E-Commerce
* Medical Records

Commercial Transaction + Open Data + Analytics = Better predictions

Walmart

* Twitter data
* local events
* local weather
* in-store purchases
* online clicks

## The Key: Integrating Diverse Data

Strucuted Data + Unstructured data + **Price Optimization** = Increased Revenue

Books about Price Optimization:

Data integration = Reduce data complexity + Increate Data availability + Unify your data system

https://www.amazon.com/Operationalizing-Dynamic-Pricing-Models-Forecasting/dp/383492749X/ref=sr_1_1?ie=UTF8&qid=1512249499&sr=8-1&keywords=Dynamic+Pricing+Models

Supply Chain Engineering: Useful Methods and Techniques

## V's for Big Data


<p align="center">
  <img src="http://www.ibmbigdatahub.com/sites/default/files/styles/xlarge-scaled/public/infographic_image/4-Vs-of-big-data.jpg?itok=4syrvSLX" />
</p>

### Volume

* Vasts amount of data
* Not just storage, we also need to be able to manage the data in a timely fashion. For processing, for instance.
* Exponential growth

### Variety

* Structural variety

Formats and models

*  Media variety

Medium in which data get delivered

* Semantic variety

How to interpret and operate on data

* Availability Variations

Real time / Intermittent

### Velocity

* Speed of generation and pace from A to B

* Real time over Batch processing

### Veracity

* Truthfullness and trustworthniness of data
* Quality

### Valence

* How much the data is connected among it self
* The valence increases over time (social network)

### Value

* How will Big Data benefit business

## Data Science: Getting Value out of Big Data

* Induce information from observations
* Big Data + Analysis + Question = Insight
* Data Science is not static, models are constantly getting better and new questions arise with new insights and data


<p align="center">
  <img src="https://i.imgur.com/9fmxxsH.jpg" />
</p>

<p align="center">
  <img src="https://i.imgur.com/67PCvf3.jpg" />
</p>

<p align="center">
  <img src="https://i.imgur.com/GJqJCzl.jpg" />
</p>

## What Data Science is made of

<p align="center">
  <img src="https://i.imgur.com/JlK7cDe.jpg" />
</p>

<p align="center">
  <img src="https://i.imgur.com/3BfA9jm.jpg" />
</p>

<p align="center">
  <img src="https://i.imgur.com/9jLykfm.jpg" />
</p>

## Building a Big Data Strategy

* Aim

1. High level goals
2. What data to collect
3. Maybe start with objectives and derive which data to get to reach them
4. Must have support from company and stakeholders

* Policy

1. Privacy and lifetime
2. Curation and quality
3. Interoperability and regulation

* Plan

* Action

## P's of Data Science

* People
1. Data Science team and project stakeholders
* Purpose
1. Focus on the question, not the technology
* Process
1. Process to iterate on, people can communicate and work together.
2. Acquire -> Prepare -> Analyse -> Report -> Act
* Platforms
1. Hadoop or other
* Programmability
1. Reusable / Reproducable / Middleware

https://words.sdsc.edu/words-data-science/data-science

## Asking the Right Questions

* Define the problem
1. e.g. How can data be used to detect machine failure
1. e.g. How can understand customer better to targeted marketing

* Access the Situation and context

* Define goal / success criteria

## Steps in the Data Science Process

1. Acquire data

* Finding data
* Retrieve data
* Query data

2. Prepare

* Explore data
* Pre process

3. Explore data

* Look the data
* Understand nature of data
* Preliminary analysis

4. Pre-process

* Clean
* Integrate
* Package into format

5. Analyse Data

* Choose analytical approach
* Build models

6. Communicate Results

* Reports
* Results

7. Apply results

**All of the above is iterative and may be repeated**

## Step 1: Acquiring Data

* Leave no stone unturned to find data
* Make use of all data
* Data comes from all places, local and remote
* Data comes in different velocities
---
* Data can come from databases (SQL and NoSQL)
* Data can come from Text files
* Data can come from websites and REST APIs

## Step 2-A: Exploring Data

* Specific characteristics of data
* Correlation
* Outliers
* Without this step, can't use data effectively
* Correlation graphs
* General trends (e.g. Sales prices increases every year)
* Mean, Median, Standard Deviation
* Visualization (heatmap, histograms, boxplots, scatter (correlation))

**Data Exploration -> Data Understanding -> Informed Analysis**

<p align="center">
  <img src="http://cdn.pythagorasandthat.co.uk/wp-content/uploads/2014/07/correlation-1-1024x675.jpg" />
</p>

## Step 2-B: Pre-Processing Data

* Clean + Transform to make it of quality
1. Inconsistent values
2. Duplicate records (constumer with same cpf)
3. Missing values
4. Invalid data (invalid CEP)
5. Outliers
6. Normalization of values

* Remove data records with missing values
* Merge duplicate records (conflicting values)
* Invalid values -> Best estimate (missing employee age, guess from how long work)
* Remove outliers, if not important for context or specific task

**All of the above needs domain knowledge to be done correctly**
