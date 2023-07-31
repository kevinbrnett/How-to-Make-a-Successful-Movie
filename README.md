![tmdb_logo](https://github.com/kevinbrnett/How-to-Make-a-Successful-Movie/blob/main/Images/tmdb_logo.png)

# How to Make a Successful Movie

Kevin Barnett

# Data Enrichment Project
Kevin Barnett

*Business Problem: What charateristics of a movie (i.e genre, rating) make it more successful than others?*

## Data Sources

## Data Filtering
The IMDB data was filtered for a specific subset of data, requested by the stakeholder.

## API Calls
API calls were made from The Movie Database (TMDB) to extract movie revenue and profit data from 2001-2022. The data was combined into one single dataframe.

## Exploratory Data Analysis
Prior to EDA being performed the data was cleaned.

**Question 1: How many movies had at least some valid financial information (values > 0 for budget OR revenue)?**
> There were 637 movies with valid financial information in the dataset.

**Question 2: How many movies are there in each of the certification categories (G/PG/PG-13/R)?**

![categories](https://github.com/kevinbrnett/How-to-Make-a-Successful-Movie/blob/main/Images/question2.png)

> **Movie Rating Counts Per Certification Category**
 > - G: 15
 > - PG: 35
 > - PG-13: 131
 > - R: 232
 > - NR: 17

**Question 3: What is the average revenue per certification category?**
![avg_rev](https://github.com/kevinbrnett/How-to-Make-a-Successful-Movie/blob/main/Images/question3.png)

> **Average Movie Revenue Per Certification Category**
> - G       $117,364,760.80
> - NR        $9,588,674.35
> - PG      $110,640,517.83
> - PG-13    $99,287,858.33
> - R        $32,465,051.61

**Question 4: What is the average budget per certification category?**
![avg_budg](https://github.com/kevinbrnett/How-to-Make-a-Successful-Movie/blob/main/Images/question4.png)

> **Average Movie Budget Per Certification Category**
> - G        $38,133,333.33
> - NR        $6,302,358.47
> - PG       $44,828,492.40
> - PG-13    $42,993,571.96
> - R        $19,484,070.91

**Question 5: What is the average profit per certification category?**
![avg_profit](https://github.com/kevinbrnett/How-to-Make-a-Successful-Movie/blob/main/Images/question5.png)

> **Average Movie Profit Per Certification Category**
> - G        $79,231,427.47
> - NR        $3,286,315.88
> - PG       $65,812,025.43
> - PG-13    $56,294,286.37
> - R        $12,980,980.71

## MySQL Database

## Hypothesis Testing

## Linear Regression Model

