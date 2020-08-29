# API - What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: **"What's the weather like as we approach the equator?"**

Now, we know what you may be thinking: "Duh. It gets hotter..."

But, if pressed, how would you prove it?

![02-Homework_06-Python-APIs_Instructions_Images_equatorsign](https://user-images.githubusercontent.com/55970064/91615814-0a6d2c00-e94a-11ea-8e75-103188be3971.png)


## Part I - WeatherPy

### Three observable trends based on the data. 

1. Max temperature of each selected city shows a strong relationship with latitude. For Northern Hemisphere, the corrlation and slope is strongly negative. Given the regression equation of Max Temperature vs. Latitude in Northern Hemisphere is y = -0.62x + 92.7, we could predict that for each one unit increase in latitude, there is 0.62 unit decrease in temperature. On the contrary, for southern Hemisphere, the corrlation and slope is strongly positive. Given the regression equation of Max Temperature vs. Latitude in Southern Hemisphere is y = 0.81x + 82.89, we could predict that for each one unit increase in latitude, there is 0.81 unit increase in temperature. 

![lat_vs_temp](https://user-images.githubusercontent.com/55970064/91622642-bf5d1400-e95d-11ea-92c2-9594bae0c534.png)


![regression_northern_temp_vs_lat](https://user-images.githubusercontent.com/55970064/91622658-d69c0180-e95d-11ea-9365-7bb87764841b.png)


![regression_southern_temp_vs_lat](https://user-images.githubusercontent.com/55970064/91622666-e1569680-e95d-11ea-9d9a-507c4e5fd3bd.png)


2. Based on this data, there is no strong relationship between Humidity vs. Latitude, and Wind Speed vs. Latitude, for both northern hemisphere and southern hemisphere. In other words, we could make the conclusion that humidity and wind speed do not differ in different latitudes. 

![lat_vs_humi](https://user-images.githubusercontent.com/55970064/91627091-6c458a00-e97a-11ea-89ff-58733692f899.png)


![lat_vs_wind](https://user-images.githubusercontent.com/55970064/91627098-7798b580-e97a-11ea-8e42-9476737896ba.png)


3. For cloudiness, altough there is no obvious trend on the overall relationship between cloudiness and latitude, there is a moderate positive relationship for cities from southern hemisphere with a regression equation of y = 0.42x + 52.92. This indicates that for each one unit increase in latitude, there is 0.42 unit increase in cloudiness for southern hemisphere cities. 

![lat_vs_cloud](https://user-images.githubusercontent.com/55970064/91627663-78cbe180-e97e-11ea-969a-d9af17fc4ff9.png)


![regression_southern_cloud_vs_lat](https://user-images.githubusercontent.com/55970064/91627675-88e3c100-e97e-11ea-994d-d5c87ac3cc5b.png)




