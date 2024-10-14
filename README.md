# Rossmann Sales Forecast 

<p align="center">
  <img src="https://images.prismic.io/flipapp-relaunch/c7d8f723-fe04-44af-a4f7-f70a68445140_rossmann-logo.png?auto=compress,format">
</p>

## Business Problem 
### Scenario
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

**Rossmann is challenging you to predict 6 weeks of daily sales for 1,115 stores located across Germany** . Reliable sales forecasts enable store managers to create effective staff schedules that increase productivity and motivation. By helping Rossmann create a robust prediction model, you will help store managers stay focused on what’s most important to them: their customers and their teams!

### Overview
The data used in this project can be found at this [Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales/data) link.

You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

### Data Fields

- **Id** - an Id that represents a (Store, Date) duple within the test set
- **Store** - a unique Id for each store
- **Sales** - the turnover for any given day (this is what you are predicting)
- **Customers** - the number of customers on a given day
- **Open** - an indicator for whether the store was open: 0 = closed, 1 = open
- **StateHoliday** - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
- **SchoolHoliday** - indicates if the (Store, Date) was affected by the closure of public schools
- **StoreType** - differentiates between 4 different store models: a, b, c, d
- **Assortment** - describes an assortment level: a = basic, b = extra, c = extended
- **CompetitionDistance** - distance in meters to the nearest competitor store
- **CompetitionOpenSince[Month/Year]** - gives the approximate year and month of the time the nearest competitor was opened
- **Promo** - indicates whether a store is running a promo on that day
- **Promo2** - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
- **Promo2Since[Year/Week]** - describes the year and calendar week when the store started participating in Promo2
- **PromoInterval** - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

## Solution Planning 

### CRISP-DS
To develop this project, we used **CRISP-DS**, a cyclical methodology for developing data science projects. The idea is to complete the project by understanding the business problem and then, after the results, go back to the beginning and try to improve the development even further. The image below shows the steps that was used to finish this project. 

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*hilp0xizP_43qVQ7wofz-w.jpeg">
</p>


## Project Stages

### Data Description
This is where I first take a look at the data, seeing its dimensions, the data types and checking for null and duplicate data. In addition, I also fill in the null data and change the data types. Finally, I did a simple descriptive statistics analysis to see the general distribution of the attributes. 

![jpg](imgs/1.png)

### 

### 

### 

### 

### 

### 

### 


## Conclusion

