# Air Quality Report 
This repository contains the code and other accompanying documents for the final project in my IoT class where I built a streaming analytics application that fetched live weather and air quality measurements from the DC area and displayed the data on a PowerBI dashboard. A python script hosted on a Raspberry Pi device fetches air quality and weather measurements from two different public APIs and sends it to the IoT Hub on Azure which further processes the data and streams it to PowerBI service. The [architecture diagram](https://github.com/ruthwikkuppachi/iot_weather_air_quality/blob/main/architecture.pdf) goes over the architecture of this system and the [placemat] (https://github.com/ruthwikkuppachi/iot_weather_air_quality/blob/main/placemat.pdf) goes over some of the use cases of this system. 

Here is a screenshot of the PowerBI dashboard which displays the data in real-time to the end-user: <img width="713" alt="Screen Shot 2022-06-13 at 4 40 49 PM" src="https://user-images.githubusercontent.com/51654907/173442363-c3904bfd-cbfc-4764-829e-273c3231fe45.png">

NOTE: This dashboard does not currently display the latest data as the script fetching the data is not running.


