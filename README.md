NCDS Python Workshop
===

> This repository holds the exercises and answers for this workshop
>
> You can find the getting started guide [here](workshop/SETUP.md)  
> and the exercises [here](exercises).

## 1. Workshop Background

### 1.1 Aims and Objectives

**Objectives**

1. Write a script to connect to NCDS API using Python
2. Authenticate using OAuth 2.0
3. Download a list of supported vaccination types
4. Create a test patient using random data
5. Create an immunization event using random data
6. Display a patient's immunization history

**Aims**

1. Aim is to reduce the mystery of connecting to an API, what's inside these APIs, and how you can integrate them into
   other applications
2. Aimed at all of NES Tech, even only semi-technical people
3. Not just targeting NCDS. Ideally you could replace "NCDS" with <any CDR component> in the near future

### 1.2 This workshop will not

1. Make you an expert at Python
2. Cover security, IG, etc, etc
3. Go into any more detail than necessary about FHIR or the specifics of NCDS

### 1.3 Who is this workshop for?

1. All of NES Tech - Technical and semi-technical
2. Data scientists, developers, technical managers
3. Front end or back end
4. Technically-oriented clinicians

### 1.4 Why Python?

1. This workshop is open to people with any background - Java, C#, front end, back end, data science, non-technical.
   Python is easy to understand even if you've never worked with it
2. Python requires very little project setup. Other languages usually have too much boilerplate code to get running in a
   couple of hours

## 2. Pre-requisites for the Workshop

### 2.1 Prior knowledge

**Python basics**

It would be useful if you knew a little Python going into this course - even if you could just read a script and
understand what's going on.

**NB:** If you've no experience programming then you'll still be able to follow along, but you might not be able to
replicate

1. `if…else…`
2. Functions / methods
3. Imports
4. pip + requirements.txt
5. venv + why venv
6. "main" method
