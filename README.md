# AQ-Track-Web

## Content
This GitHub Repository includes: 
- the folder "raspi-sensors", which includes code for measuring the air quality with a Raspberry Pi and the following sensors: 
    - SDS011
    - HM3301
    - Grove - Mehrkanal-Gassensor V2

- the folder "data-analysis", which includes code for cleaning, transforming and analysing the measured values and created diagrams.

- the folder "website", which includes code for visualising the measured values on a local web application. 

## Context
This Repository was created for my bachelors thesis.  
The topic is: "Entwicklung eines Prototyps einer Messgeräteerweiterung zur Erfassung von Luftdaten und Darstellung der gemessenen Daten in einer Webanwendung"  
(engl. "Development of a prototype of a measuring device extension for the acquisition of air data and display of the measured data in a web application")  

## Starting the web application
1. You must have Python on your computer. 
2. Navigate to the downloaded folder in the command prompt and start a local server with: ```python -m http.server 8000```
3. Open a new window in your browser and type: http://localhost:8000/website/DEMO.html 

### Information for the web application 
The data from the point located at the Schillerallee 1 are based on air quality measurements of the sensors (SDS011, HM3301, Grove - Mehrkanal-Gassensor V2).  
The data from the other point, located at Käthe-Kollwitz-Str., are only example data and were created to test the functionality of the web application.  