# Titanic Survival by Age Analysis

I built this small project to understand how age is related to survival in the Titanic dataset.

In this project, I used the Titanic dataset from seaborn and focused only on the `age` column and the `survived` column. I first checked how many age values were missing because missing data can affect the analysis. After that, I removed the rows where age was missing so the plots would be more accurate.

Then I created two visualizations.

The first one is a histogram with KDE. I used this to see the age distribution of passengers and compare survivors and non-survivors in the same plot. This helped me understand how different age groups were distributed.

The second one is a KDE plot. I used this to get a smoother view of the age distribution for passengers who survived and passengers who did not survive. This made it easier to compare the patterns between the two groups.

## What I did in this project

- loaded the Titanic dataset
- checked missing values in the age column
- removed rows where age was missing
- plotted age distribution by survival using histogram
- plotted age distribution by survival using KDE plot

## Why I did this project

I did this project to practice basic data analysis and visualization. I wanted to understand how to explore a real dataset, clean missing values, and compare two groups using plots.

## Tools I used

- Python
- seaborn
- matplotlib

## What I learned

From this project, I learned how to:

- load datasets using seaborn
- check missing values
- clean data before plotting
- compare survival groups using visualizations
- understand patterns in the data using histogram and KDE plots

## Output of the project

This project gives:

- the number of missing age values
- a histogram showing age distribution by survival
- a KDE plot showing smooth comparison of age by survival

## How to run

1. Open the code in Google Colab or Jupyter Notebook
2. Run the code
3. Check the printed missing values count
4. View the histogram and KDE plots

## Project goal

The goal of this project is to understand whether age shows any visible pattern in relation to survival in the Titanic dataset.
