# airbnb

I was graduated from Upschool(https://www.upschool.io/?lang=en) in October,2020. 
My capstone project was about airbnb hiring project on Kaggle.(https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings) In 2015, Airbnb launched a challenge about new user bookings, it was expected to predict first destination of new users.
The data of real users, who lived in USA, from 2010 -2015 was included in train data. There were 12 possible outcomes of destionation : 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF'(no destination found), and 'other'.Other means the remainin countries, NDF means there was no booking.

It is a supervised, discrete problem. Because of the that, the problem type is classification. There is 12 classess, so it is a multiclass classification problem.

I analyzed my training data and handled outliers, missing values, wrong values by removing or imputing them. I used decision tree, random forest and XGboost methods to predict destinations.
The data is imbalanced, so it is challenging the predict the countries which were chosen to book barerly. For further steps, I may try to solve these problem more.
