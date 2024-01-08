**IoT Platform Documentation**

**Project Overview:**

-   Develop an IoT platform to manage sensor data, including:

    -   Sensor registration

    -   Data reception and storage

    -   Data retrieval and visualization

**Introduction :**

This document provides details on the implementation and usage of the
IoT platform. The platform allows users to register sensors, receive
data through REST APIs, store the data, and retrieve it as needed.

**Requirements:**

**1.Sensor Registration :**

-   It allows the Users to register sensors on the platform.

-   Here is the .CSV File data recorded by thw Sensors


-   The above provided are the Air Quality,Water Qualiy and Soil Quailty
    CSV files recorded by the sensors,

**2.Data Reception :**

-   Here The IOT(INTERNET OF THINGS) platform will accept the data
    collected from the sensors

**HardWare Simulator :**

**Sensor Simulation:**

Simulates three Different sensors :AQ,SR-AQ,WM-WD

**Data Generation :**

Here It Will Generate Data in the CSV specified Format Files.

**Data Posting :**

Periodically post the Sensor Data to the IOT platform and visualize
using ReCharts in the frontend.

### **Data Visualization:**

**1.Data Fetching:**

Fetching the data from the sensor collected CSV Files to the
Frontend and the visualization of the imported csv data begins.

**2.Visualization:**

Visualizing data using charts/graphs to show trends and other
information to make it easier to understand

**3.Real-time Updates:**

Ensure real-time updates as new data is added to the platfrom have to
update the Sensor collected Data for better users friendlu experience.

**IMPLEMENTATION :**

-   FrontendTechnology :

> Here I have used Rect.js for the frontend for Building the Visualization interface.

-   Charts/Graphs :

> I implement different types of charts/graphs based on the sensor data

-   Real-Time Updates:

> Update the visualization in real-time as new data is received

**FLOWCHART :**

SENSOR REGISTRARTION

**Users register sensors on the IoT platform.**

SIMULATOR

**Simulate sensors and periodically post data to the IoT platform.**

IMPORTING .CSV FILE

Here I import the direct csv sensor recorded files

DATA VISUALIZATION

We will fetch the data from the imported files and visualize in the
frontend

**Frontend Of The IOT Sensor Data Analysis :**

The Frontend Page of the IOT(INTERNET OF THINGS) platform looks in the
below format ...
![WhatsApp Image 2024-01-07 at 20 41 52_93e00f7f](https://github.com/krishkrishna03/MACHINE_LEARNING_PROJECT/assets/96357392/5e258734-2d84-4bc7-8243-cfa6223511ca)

So the above is about all the 3 sensor dedicated data ,so for each we
also made the predictions just like the below provided...by having a
click on the Air Quality View button it gives us the prediction in the
as like
![WhatsApp Image 2024-01-07 at 20 41 52_ff42eb12](https://github.com/krishkrishna03/MACHINE_LEARNING_PROJECT/assets/96357392/7f42c4e5-bf4f-4f36-8d22-843a53b8f277)


Now by going through the next view of soil quality we can obtain as
follows...

![WhatsApp Image 2024-01-07 at 20 41 53_7f3516ff](https://github.com/krishkrishna03/MACHINE_LEARNING_PROJECT/assets/96357392/6684c387-463c-496e-8f67-d7c981370731)


**NOW by going through the Water Quality we can get the prediction as
follows.....**

![WhatsApp Image 2024-01-07 at 20 41 54_10e0772b](https://github.com/krishkrishna03/MACHINE_LEARNING_PROJECT/assets/96357392/18284e68-8bde-40d4-a9d1-7551f4920ed4)


**Data Visualization :**

![WhatsApp Image 2024-01-07 at 20 41 53_48dd2e04](https://github.com/krishkrishna03/MACHINE_LEARNING_PROJECT/assets/96357392/1fad352a-5c15-47c6-8713-04b0719f27b1)


![WhatsApp Image 2024-01-07 at 20 41 54_48b30f9b](https://github.com/krishkrishna03/MACHINE_LEARNING_PROJECT/assets/96357392/234e5552-9579-4a2b-8561-9703088cb2cd)

**Prediction Analysis :**

-   *For predicting Air Quality I used the Machine Learning Algorithm
    called Linear Regression*

-   *For predicting Soil Quality I used the Machine Learning Algorithm
    called Decision Tree*

-   *For predicting Water Quality I used the Machine Learning
    Algorithm called Random Forest.*
    
**Follow below steps to run the task:**
  
-   As I only use React.JS to develop the whole task, just need to import required files of React
-   *npm install* - It installs all required files for the task.
-   *npm start* - It starts the execution and leads you to the landing page of the website.
