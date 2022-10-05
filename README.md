# Uber-data-analysis
### Uber Data Analysis : Case Study 1   
| [Click here for the code](https://www.kaggle.com/code/diplod0cus/uber-data-analysis-case-study-1) |   
![image](https://user-images.githubusercontent.com/38161827/193102369-6e113f10-54b0-40ea-a311-1bdc714f3e44.png)

#### Dataset details: 
Dataset name : [My Uber Drives (2016)](https://www.kaggle.com/datasets/zusmani/uberdrives)  

Dataset Contents:
- Geography: USA, Sri Lanka and Pakistan
- Time period: January - December 2016
- Unit of analysis: Drives
- Total Drives: 1,155
- Total Miles: 12,204
- contains Start Date, End Date, Start Location, End Location, Miles Driven and Purpose of drive (Business, Personal, Meals, Errands, Meetings, Customer Support etc.)
- Aim : To learn from the behavior of an ordinary Uber customer.

<a id="top"></a>
<div class="list-group" id="list-tab" role="tablist">
<h3 class="list-group-item list-group-item-action active" data-toggle="list" role="tab" aria-controls="home">  Table of Content</h3>
    
   * [Data acquisition](#1)
   * [Missing Value Handling](#2)
   * [Duplicate Rows Handling](#3)
   * [Renaming Columns](#4)
   * [Replace Null values](#24)
   * [Introduction of MONTH and Related Visualization ](#25)
   * [Exploratory Data Analysis](#5)
   * [Questions :](#6)
        * [1. Top 10 starting location](#7)
        * [2. Which was the most Frequent Starting Point?](#8)
        * [3. Top 10 STOP locations](#9)
        * [4. Which was the most Frequent Stopping Point?](#10)
        * [5. What is the number of trips per month?](#11)
        * [6. What is the number of trips per day? ](#12)
        * [7. How many trips for each purpose?](#13)
        * [8. How many trips in any particular day of all months (Category-wise) ?](#14)
        * [9. How many trips in any weekday?](#15)
        * [10. Is there any Round Trip? If, Yes, then How many Round Trips?](#16)
        * [11. Calculate Ride durations and Analyse](#17)
        * [12. Show Month-wise number of Uber Rides](#18)
        * [13. At which day uber rides were mostly used?](#19)
        * [14. Which was the Longest and the Shorest Ride Months (Based on Average Distance covered per month)?](#20)
        * [15. When was the Max no. of Trips in a day generally?](#21)
        * [16. Speed](#22)
   * [Save the Result](#23)
   
  #### Answers 
  * [1. Top 10 starting location]()  
  
    ![image](https://user-images.githubusercontent.com/38161827/194129634-1b5f6ebb-e60f-4325-b7d9-89d7cd9bc44d.png)
  * [2. Which was the most Frequent Starting Point?](#8)
  
  ![image](https://user-images.githubusercontent.com/38161827/194130041-705c2dd7-e19b-4a2e-8c70-45f3f6226eba.png)

  * [3. Top 10 STOP locations](#9)
  
  ![image](https://user-images.githubusercontent.com/38161827/194130066-7fcd86f0-48d9-4cd6-becc-25459cff9720.png)

  * [4. Which was the most Frequent Stopping Point?](#10)
  
  ![image](https://user-images.githubusercontent.com/38161827/194130092-f5aee88d-7098-4890-b2db-f470a15e7195.png)

  * [5. What is the number of trips per month?](#11)
  
  ![image](https://user-images.githubusercontent.com/38161827/194130191-efc98d18-dbb2-46da-812a-02651b3a0676.png)

  * [6. What is the number of trips per day? ](#12)
  
  ![image](https://user-images.githubusercontent.com/38161827/194130215-bd1fbdea-83cb-4c67-87b7-26e5b040f35b.png)

  * [7. How many trips for each purpose?](#13)
  * [8. How many trips in any particular day of all months (Category-wise) ?](#14)
  * [9. How many trips in any weekday?](#15)
  * [10. Is there any Round Trip? If, Yes, then How many Round Trips?](#16)
  * [11. Calculate Ride durations and Analyse](#17)
  * [12. Show Month-wise number of Uber Rides](#18)
  * [13. At which day uber rides were mostly used?](#19)
  * [14. Which was the Longest and the Shorest Ride Months (Based on Average Distance covered per month)?](#20)
  * [15. When was the Max no. of Trips in a day generally?](#21)
  * [16. Speed](#22)
