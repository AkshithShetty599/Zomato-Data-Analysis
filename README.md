# Zomato Data Analysis

This project performs an exploratory data analysis (EDA) on Zomato's restaurant data. The analysis includes various visualizations and insights to understand different aspects such as restaurant types, votes, ratings, and more.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data Overview](#data-overview)
- [Data Preprocessing](#data-preprocessing)
- [Analysis and Visualizations](#analysis-and-visualizations)
  - [Memory Usage Reduction](#memory-usage-reduction)
  - [Restaurant Count by Category](#restaurant-count-by-category)
  - [Votes Based on Restaurant Types](#votes-based-on-restaurant-types)
  - [Top 5 Restaurants Based on Votes](#top-5-restaurants-based-on-votes)
  - [Online vs Offline Orders](#online-vs-offline-orders)
  - [Ratings Distribution](#ratings-distribution)
  - [Approximate Cost for 2 People](#approximate-cost-for-2-people)
  - [Online vs Offline Orders Based on Ratings](#online-vs-offline-orders-based-on-ratings)
  - [Online vs Offline Orders Based on Restaurant Types](#online-vs-offline-orders-based-on-restaurant-types)
- [Conclusion](#conclusion)

## Introduction

This project aims to analyze Zomato's restaurant data to extract meaningful insights. The analysis covers aspects such as restaurant types, votes, ratings, and cost distribution.

## Installation

To run this project, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn

## You can install the required libraries using pip:

pip install pandas numpy matplotlib seaborn

# Data Overview
The dataset contains information about various restaurants listed on Zomato. The data includes the following columns:

* name: Name of the restaurant
* online_order: Whether the restaurant accepts online orders
* book_table: Whether the restaurant accepts table bookings
* rate: Rating of the restaurant
* votes: Number of votes the restaurant has received
* approx_cost(for two people): Approximate cost for two people
* listed_in(type): Type of restaurant (e.g., dining, cafe, etc.)

# Data Preprocessing

## Memory Usage Reduction
The data types of some columns were converted to smaller data types to reduce memory usage.

# Analysis and Visualizations

## Restaurant Count by Category
A count plot to show the number of restaurants in each category.

## Votes Based on Restaurant Types
A line plot to show the sum of votes for each restaurant type.

## Top 5 Restaurants Based on Votes
A bar plot to show the top 5 restaurants based on the number of votes received.

## Online vs Offline Orders
A pie chart to show the percentage distribution of online and offline orders.

## Ratings Distribution
A histogram to show the distribution of ratings.

## Approximate Cost for 2 People
A count plot to show the approximate cost for two people at different restaurants.

## Online vs Offline Orders Based on Ratings
A box plot to compare ratings between online and offline orders.

## Online vs Offline Orders Based on Restaurant Types
A heatmap to show the comparative analysis of online orders based on restaurant types.

# Conclusion
* Majority of the restaurants fall into the dining category.
* Dining restaurants are preferred by a larger number of individuals.
* The restaurant with the maximum votes is Empire Restaurant.
* A majority of the restaurants do not accept online orders.
* The majority of restaurants received ratings ranging from 3.5 to 3.75.
* The majority of couples prefer restaurants with an approximate cost of 300 rupees.
* Offline orders received lower ratings compared to online orders.
* Dining restaurants primarily accept offline orders, whereas cafes primarily receive online orders.

