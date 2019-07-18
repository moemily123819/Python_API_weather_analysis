# ***Python API***

 

### **Objective :**

Write a python script to find out if there is any co-relation between the latitude of a city and its weather attributes namely maximum temperature, wind speed, humidity and cloudiness.

 

### **Author :**

Emily Mo

 

### **About the data and the process :**

A thousand and five hundred pairs of latitudes and longitudes are randomly generated (between -90 to 90 for latitude and -180 to 180 for longitudes).  These pairs are fed into citipy to find the nearest city.  The number of cities will be drastically lower than 1500 as some pairs fall into oceans or uninhabited areas.  

The weather conditions of these cities are retrieved real-time using openweathermapy API.  The maximum temperature, cloudiness, humidity and wind speed are collected and plots against latitudes. 

Conclusions will be drawn upon these plots.

 

### **About the python script :**

This python script uses :

- matplotlib to plot, 

- numpy for np.random,

- citipy to locate the nearest city for a pair of randomly generated latitude and longitude

- openweathermapy API, 

- output to a csv file, 

- array processing including zip to zip latitudes and longitudes, 

- pandas dataframes,

- and clean data in case of nan. 

  



### Deployment :

The python script, weatherPy.ipynb can be called in jupyter notebook.

