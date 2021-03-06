# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
*Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?*

The variables vehicle_wieght, spolier_angle, and AWD provide a non-random amount of variance. However, ground_clearance and vehicle_length had provided a random amount of variance.

*Is the slope of the linear model considered to be zero?*

The slope is not considered to be zero (0), becuase when we see the p-value, it is very less than 0.05. Also, this linear regression shows that some of the independent variables had an effect on the dependent variables, and if thre was no effect I would have considered the slope to be zero. 

*Does this linear model predict mpg of MechaCar prototypes effectively?*

I would consider this linear model of predicting the mpg of MechaCar prototypes to be effective, considering our R^2 value is 71.49%, which means that there is a 71.49% chance that we will predict the mpg values correctly, or out of 100 instances, we will approximately predict the mpg of the MechaCar correctly 71 times. 

![Screenshot (194)](https://user-images.githubusercontent.com/58046234/161389547-b785cfa6-d810-4d36-bc46-f2ba2614eb10.png)
![Screenshot (195)](https://user-images.githubusercontent.com/58046234/161389548-f042f8b4-1f5d-4fb2-ae53-8faa4a876309.png)

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. *Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually?* Lot 1 and Lot 2 are within the design specifications and have nearly the same mean and median. In Lot 3, there is a high variance and it exceeds the manufacter's specifications. So, the manuafacturing team should choose cars that are in Lot 1 and Lot 2.  

![Screenshot (198)](https://user-images.githubusercontent.com/58046234/161389612-89aff48a-39d0-4a2d-94d7-cf4ace1ccf90.png)
![Screenshot (199)](https://user-images.githubusercontent.com/58046234/161389608-ea5005b6-c48c-44d8-8797-d56273f67fb6.png)

## T-Tests on Suspension Coils

By using a significance level of 95%, meaning that 95% of the time this tests results would be true. For Lot 1, we fail to reject the null hypothesis because the p-value equals 1. For Lot 2, we fail to reject the null hypothesis again because the p-value equals 0.6072. However, for Lot 3, we can reject the null hypothesis again because the p-value equals 0.04168.

![Screenshot (200)](https://user-images.githubusercontent.com/58046234/161390435-f5d00ea8-e8c3-415c-8d68-b5d7e7b8ac20.png)
![Screenshot (201)](https://user-images.githubusercontent.com/58046234/161390438-88ac12e8-9f72-4285-a873-221df3db7b90.png) ![Screenshot (202)](https://user-images.githubusercontent.com/58046234/161390442-5ec79c48-77d8-4e6d-8a84-1bf848135d61.png)

## Study Design: MechaCar vs Competition
This study was about comapring MachaCar's models and diffrent manufactures in the last 3 years.

What metric or metrics are you going to test?
- Safety Feature Rating, Malfunctions/recalls, Current Price, Type of Engine (ex. electric, gasoline, etc.), Average Cost of Ownership, MPG, etc.
What is the null hypothesis or alternative hypothesis?
- The null hypothesis is that MechaCar is fairly priced based on its performance of key factors for its genre.
- The alternative hypothesis is that MechaCar is *not* priced correctly based on performance of key factors for its genre.
What statistical test would you use to test the hypothesis? And why?
- A multiple linear regression could be used to determine the factors that have the highest correlation with the list selling price. We can also see which 2 variables together can imapact the list selling price.

