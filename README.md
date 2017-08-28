
# Google Summer of Code 2017 : Project Repository , Database Visualization Dashboard for Urban Energy Systems Laboratory, Empa
Project Title : Visualization Dashboard for Empa-NEST
Mentors : Fricker Reto , Philipp Heer
By : Arushee Garg
----------------------------------------------------------
Open source visualization dashboard for Empa-NEST: using Node-red
Github Link : https://github.com/arugarg/GSOC2017-VisualizationDashboard-EmpaNest
----------------------------------------------------------
Introduction 


Data on the Empa NEST  is highly diverse and rapidly growing. Currently, this data is stored in separate platformsthe trend data in MSSQL and live data in OPC UA. The aim of this project is to develop an open source visualization dashboard integrated into a Website based on Node-Red and javascript charting library Highcharts which will have a connection to the Microsoft SQL Database and OPC UA server. The trend data is logged into a SQL Database in the NEST-Cloud, which is accessible for researchers and technicians from all over the world. And the live data will be accessible via OPC UA server. To bring the big data to life it is essential to have attractive visualization charts. Visual representations using graphical structures will help the researchers and practitioners for the development of models and analyses of distributed energy systems.

Node Red is a recent programming tool developed by IBM for wiring together hardware devices, APIs and online services in new and interesting ways. Will be implementing Node-red with libraries- SQL node connection, OPC - UA server, Dashboard UI nodes , http nodes and  javascript charting library Highcharts for creating the visualization dashboard and MS SQL querying for plugging in the data.

---------------------------------------------------------
The Dashboard can be accessed at the local where node-red runs or at http://192.168.223.70:1880/ui/#/0

![Settings Window](https://raw.github.com/arugarg/GSOC2017-VisualizationDashboard-EmpaNest/resources/images/IndividualSignal.png)
![Weather Station](/relative/path/to/img.jpg?raw=true "Weather Station")

-------------------------------------------------------
Pre requisites:
1. Node-red installed
2. Connection to Empa NEST MSSQL DB
Modules in node-red:
1. Node-red-contrib-mssql
2. Node-red-contrib-opcua
3. node-red-dashboard

-------------------------------------------------------
Work Done:
Display of Individual Signal Tab
Display of all the signals involving Weather Station
Display of selective live OPC UA signals in Live Dashboard

Work Left :
Addition of further signals to Individual Signal Tab
Cumulating signal groups as done in Weather Station
Adding more signals to Live Dashboard
 
--------------------------------------------------------
