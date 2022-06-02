# FEMIN_Portfolio
Meteorological &amp; Environmental data analysis

# [Air Quality Analysis (OpenAir-rpy2)](https://github.com/eminfe/AirPollution-OpenAir-)
The wind data from the meteorology station and the data from the air pollution measurement station were analyzed using the rpy2 library.

LOCAL AIR QUALITY ANALYSIS OF LODZ GDANSK USING THE R OPENAIR PACKAGE VIA RPY2
Location : Łódz, Czernika 1/3
WMO ID : 12465
Airbase Code: PL0543A
Load Python and R libraries, activate the rpy2 pandas2ri conversion class, and connect some R functions to Python symbols.

![](/images/1.png)
![](/images/CalPlotO3.png)
![](/images/Hourly_PM10.png)
![](/images/Filter_polarFreq_PM10.png)
![](/images/TimeVariation_O3.png)
![](/images/timePlotPM25.png)


# [Climate Analysis Ataturk Airport(R-GSODR)](https://github.com/eminfe/ClimateAnalyse_AtaturkAirport)
The aim of this study is to make a 30-years climate analysis for 
Istanbul Ataturk Airport by evaluating the temperature and precipitation data from 1990 to 2020.

Coordinates: N40°58.57' / E28°48.85'
Elevation: 33m
Station name & code: Atatürk Airport & LTBA
Country: Turkey

Data were obtained from GSOD (link) database and processes using R language 

![](/images/Figure7.png)
![](/images/Figure8.png)
![](/main/images/Figure10.png)

# [Food Store OOP (Python)](https://github.com/eminfe/FoodStore_OOP-Python-)

STOCK MANAGEMENT IN FOOD STORE 

Food Store, selling the below mentioned items:
Item          Quantity (in numbers)      Price (per unit)-(in PLN)
Bread                20                        2
Muffins              50                        3
Cake                 30                       2.5
Cookies              100                      0.5
A program is required to show the following:
✓ Price list of items
✓ Initial stock availability
✓ Initial stock value of each item
✓ Purchase details
✓ Updated stock after purchase
✓ Updated stock value after purchase

Set the class as Foodstore.
Define the set of items’ quantity and price as dictionaries.
Set the hierarchy as: items, quantity and price.
Add the above list of items as initial stock – by calling a method to add the items’ name, quantity and price.
Display the initial stock and stock value after evaluation.
User will be prompted to provide purchase details.
User can enter the number of distinct items he is going to purchase, item name and quantity. Below validations are incorporated in the user inputs:
If the input number of purchase items is greater than 4, system will generate a ValueError – number of items cannot be greater than 4.
User can select items only from the above list of 4 items. If the input item name is different, system will generate ValueError – Order can be placed only for the above items.
Purchase order will be displayed.
System will update the stock by calling corresponding method. Below validations are incorporated:
If the ordered quantity is greater than stock balance of the ordered item, system will generate ValueError – Required quantity is not available.
Updated stock and stock value will be displayed after purchase.

# [PM10_TimeSeries](https://github.com/eminfe/PM10_TimeSeries)

This Python program would pass over all the .CSV files in the given directory, and for each of these files produce plots saved as .PNG or PDF files. Each of these plots named after its source .CSV file. (Numpy, Pandas & matplotlib libraries are used)

![](/images/time_series.png)
![](/images/DsDuszniMOB.csv.png)
