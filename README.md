# Data Analysis of Ford GoBike

## Introduction
**Ford GoBike** is a **public bicycle sharing platform** in _San Francisco_. For ease of transportation, **bicycles are available for the people at any point of time**. Either you can become a subscriber or avail this service as a customer.
This dataset has **details of users** like what was the _starting point, end point, age of user, duration_ and many more.
This dataset has **_183412 rows_** and **_16 columns_**.

## Questions
> ### Main features/Point of Interest of Dataset are:

>    - Most common start and end stations.
>    - Gender.
>    - Different Age groups.
>    - Riding Durations.
    
## Exploratory Data Analysis
During Exploration, I found out few patterns and also visualized the relationship between various factors which are listed below:

>    1. Common **starting point** for majority of users was **Market St at 10th St** and **ending point** was **San Francisco Caltrain Station 2.**
>    2. Majority of users are Male's
>        1. Male - 74.6%
>        2. Female - 23.3%
>        3. Other - 2.1%
>        ![image](https://user-images.githubusercontent.com/48478512/121375066-10268200-c95e-11eb-85ac-99fdd2c017d2.png)
>    3. _While exploring age features, Outliers were found which helped me to improve the quality of data by removing outliers and improving the accuracy of Data Analysis._
>    
>        ![image](https://user-images.githubusercontent.com/48478512/121375189-2b918d00-c95e-11eb-84b1-3c740d1bef0a.png)
>    4. Majority of users are Subscribers and few Customers.
>    
>        ![image](https://user-images.githubusercontent.com/48478512/121375260-3ba96c80-c95e-11eb-94ec-d645b1b7d946.png)
>    5. Use of bike on weekdays is more as compared to weekends. By this I concluded that people use bike to reach their workplace.
>    
>        ![image](https://user-images.githubusercontent.com/48478512/121375384-54b21d80-c95e-11eb-95af-ccb8db24ced9.png) 
>    6. Majority of Subscribers have there work place near to the start point as they require less time to reach their destination.
>    
>        ![image](https://user-images.githubusercontent.com/48478512/121375858-ae1a4c80-c95e-11eb-9e84-871f7a1cc0c2.png)

## Resources Used

>    1. Technology used:
>       1. Python and Libraries(Pandas, NumPy, Seaborn, Matplotlib)
>       2. GitHub
>    2. Official Documentation
>       1. Pandas - https://pandas.pydata.org/docs/
>       2. Seaborn - https://seaborn.pydata.org/
>    3. Book - **Data Science from Scratch** by _Joel Grus_
>    4. Udacity Data Analysis Course.
