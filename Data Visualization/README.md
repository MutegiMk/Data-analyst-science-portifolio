# (Melbourne Housing Dataset Exploration)
## By (Emmanuel Mutegi)


## Dataset

> The entire dataset is comprised of 21 variables with 8 variables as characters or strings. Before moving onto the effect on the target variable (Price) by those 8 variables. Every row in the dataset denotes information about property (house, townhouse etc) , price it is sold for, seller information and more characteristics such as number of bedrooms, location (latitude, longitude etc).It's a real estate dataset with a lot of insights. I sourced my dataset at **Kaggle**. My dataset was faily clean in respect to my columns of interest and did not perform a lot of cleaning but I did a few by replacing abbreviated names with distinct names like (House,Unit,TownHouse) and also converting Car column to int.


## Summary of Findings

>The distribution of the prices of real estate follows a unimodal distribution with an average around 600k dollars with the transformed data.
>Houses with 3 rooms seems to be the most built and 10 room houses are the least built in the region
>House(cottage,villa,terrance) takes the largest portion which is more of residential and townhouse is the least.
>Most buildings are located between 0 and 15 kilomettres away from the cbd and the highest number found at around 11 kilometres.
>Most Residentials have 1 or 2 carspot and the highest carpot record is 10. The data is right skewed with a largest frequency at 1-2 carpots.
>Southern Metropolitan has the highest number in terms of real estate  while Western Victoria has the least number.
>Most landsizes are between 300 and 1000 metres and the peak most is at around 990 metres based on transformed data.
>Buldings with one bathroom are dorminant while buldings with 7 and 8 bathrooms being the least
>There is a positive non-linear relationship( that's ‘as x increases, y increases rapidly at first and then more slowly) between number of bathrooms and price where 1 bedroom is more dorminant ,most high prices fall under 1 to 4 bedrooms
>Prices vary among diferent regions with southern having the highest median and western victoria trailing
>Unit type has a wider section representing a higher probability that investors will take on a given value while house has a lower probality but has a relative higher median
>There are few differences interms of Distance between Types,the medians are consistent across the Three box plots, the boxes are fairly similar in sizes, and all Types have outliers at maximum ends, with Type House with most outliers indicating that more House buildings are  far from CBD
>House(cottage,villa,mansion) has the more bathrooms than the rest, this can be attributed to individual ownership and the rationale of No. of bathrooms depends on the owner and number of people living in that house
>Unit boxplot visual portrays there exists no value smaller than the median on matter of parcel of land the construction is built.




## Key Insights for Presentation

> The positive Relationship between Price, Distance and Types of residential
> Interesting Interaction between Type,price and Regions?
> The relationship between regions and price?
> Prices interaction with Number of bathrooms
