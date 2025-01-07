<!-- ---
title: "List of Irregular Verbs Across Romance Languages" 
date: 2013-03-07
lastmod: 2024-07-12
tags: ["Romance languages","philology","irregular verbs","Portuguese","Italian","French","Spanish","simulations","dataset","python"]
author: ["Patrick Fitzcarron O'Leary","Florianus Prinzel","Walter Schoeffler-Henschell","Detlev Amadeus Unterholzer", "Dieter Vogelsang","Moritz-Maria von Igelfeld"]
description: "This dataset contains all irregular verbs in known Romance languages."
summary: "This dataset contains all irregular verbs in known Romance languages."
editPost:
    URL: "https://github.com/pmichaillat/hugo-website"
    Text: "GitHub repository"
showToc: true
disableAnchoredHeadings: false

--- -->

<!-- ## Overview

This dataset contains all irregular verbs in [all known Romance languages](http://www.alexandermccallsmith.com/series/von-igelfeld-series)—including Portugese, Spanish, French, and Italian. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

--- -->

## Work

+ Rice University - Research Assistant 
### Prof. Tommy Pan Fan 
##### Prof. Tommy Pan Fan 
+ Shell - Software Engineer Intern
##### AiOps & App Monitoring Tools 
+ The University of Texas at Austin - Research Assistant 
##### Prof. Antonio Linero

## Extracurricular 


<!-- 
+ M 341 – Linear Algebra and Matrix Theory 
+ M 362K – Probability I
+ STA 235H – Data Science for Business Applications: Honors
+ SDS 320E – Elements of Statistics
+ STA 301 – Introduction to Data Science 

## Business Courses  

##### Management 

+ O M 235H – Operations Management: Honors
+ MAN 327H - Innovation/Entrepreneurship: Honors
+ MIS 375 – Strategic Information Technology Management

##### Accounting + Finance 

+ ACC 311H – Fundamentals of Financial Accounting: Honors
+ ACC 312H – Fundamental Managerial Accounting: Honors

##### Communication & Professional Development

+ B A 324H – Business Communication: Oral/Written: Honors
+ B A 151H – Honors Lyceum in Business Administration

## Random Fun Electives

##### ⋆｡‧˚ʚ♡ɞ˚‧｡⋆

+ UGS 303 – Sleep: Are We Getting Enough?
+ MUS 307 – Jazz Appreciation
+ R S 310 – Intro to the Study of Religion
+ R S 315N – Intro to the New Testament
 -->

<!-- ## Junior Year

##### Fall 2024

+ MIS 333K – Web Application Development
+ M 341 – Linear Algebra
+ M 362K – Probability 1
+ MIS 375 – Strategic Information Technology Management 
+ RS 315N – Intro To The New Testament 

## Sophomore Year 

##### Spring 2024

+ O M 235H - Operations Managements: Honors
+ D S 235H - Into to Decision Science: Honors
+ ACC 312H - Fundamental Managerial Accounting: Honors 
+ MIS 373 - Technical Dimensions of Cybersecurity
+ C S 303E - Elements of Computers/Programming 
+ MIS 304 - Intro Problem Solving/Programming
+ UGS 320K - Undergraduate Research 

##### Fall 2023

+ STA 235H - Data Science for Business Application: Honors 
+ ACC 311H - Fundamentals of Financial Accounting: Honors
+ MAN 327H - Innovation/Entrepreneurship: Honors
+ B A 324H - Business Communication: Honors 
+ B A 151H - Honors Lyceum in Business Administration
+ MIS 325 - Database Management 
+ SDS 320E - Elemenets of Statistics 
 -->


<!-- ## View dataset

+ Irregular verbs in Portugese: [data](https://github.com/pmichaillat/feru)
+ Irregular verbs in Italian: [data](https://github.com/pmichaillat/unemployment-gap)
+ Irregular verbs in French: [data](https://github.com/pmichaillat/job-rationing)
+ Irregular verbs in Spanish: [data](https://github.com/pmichaillat/countercyclical-multiplier)

---

## Source of data

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


---

## Using data with Python

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Start Python:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

```python
import numpy as np
import pandas as pd
```

### Open the file:

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat `data.csv`.

```python
file_path = 'data.csv'
with open(file_path, 'r') as file:
```

### Read data:

Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.

```python
    lines = file.readlines()
```

### Parse and process data:

Duis aute `line_data` irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur `data.extend`.

```python
data = []
for line in lines:
    line_data = line.strip().split(',')  # Split the line into a list of values
    line_data = [float(value) for value in line_data]  # Convert values to floats
    data.extend(line_data)  # Extend the main list with values from the line
```

#### Compute summary statistics using NumPy:

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum: `data_array`. 

```python
data_array = np.array(data)  # Convert the list to a NumPy array
mean = np.mean(data_array)
median = np.median(data_array)
std_dev = np.std(data_array)
min_value = np.min(data_array)
max_value = np.max(data_array)
```

#### Display summary statistics:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat `print`.

```python
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Standard Deviation: {std_dev}")
print(f"Minimum Value: {min_value}")
print(f"Maximum Value: {max_value}")
```
 
---

## Description of simulation parameters

| Parameter |   Value   |  Language  | Time period |           Description            |
| :-------: | :-------: | ---------- | :---------: | :------------------------------: |
|  $\alpha$ |   $1/2$   | French     |  1930–1954  |         Tempor dolor in          |
| $\lambda$ |   $e/2$   | French     |  1930–1954  |       Fugiat sint occaecat       |
|  $\gamma$ |  $\ln(3)$ | Spanish    |  1833–1954  |      Duis officia deserunt       |
|  $\omega$ | $10^{-4}$ | Italian    |  1930–1994  | Excepteur et dolore magna aliqua |
|  $\sigma$ |   $1.5$   | Portuguese |  1990–2023  |         Lorem culpa qui          |
|  $\chi^2$ |  $\pi^2$  | Portuguese |  1990–2023  |         Labore et dolore         | -->
