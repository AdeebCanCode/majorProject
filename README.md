# majorProject
Smart manhole monitoring system that I created for my final year project.

**ABSTRACT :**
A smart city is a future goal to have cleaner and better amenities for society. Smart
underground infrastructure is an important feature to be considered while implementing
a smart city. Drainage system monitoring plays a vital role in keeping the city clean and
healthy. Since manual monitoring is incompetent, this leads to slow handling of
problems in drainage and consumes more time to solve. To mitigate all these issues,
the system using a wireless sensor network, consisting of sensor nodes is designed.
The proposed system is low-cost, low maintenance, IoT-based real-time which alerts
the managing station through an email when any manhole crosses its threshold values.
This system reduces the death risk of manual scavengers who clean the underground
drainage and also benefits the public.
Nowadays, accidents due to broken and missing manhole covers are quite frequent.
Manholes are not monitored properly in developing countries. These accidents can lead
to serious injuries and also death. Hence, here we propose a system to overcome this
problem. We have included an array of sensors for complete monitoring of the manhole
cover so that such accidents can be prevented. This project includes a gas cover to
monitor the gas emitted from the sewage systems so that toxicity can be monitored, the
internal temperature is also monitored if a check for a change in the temperature as the
property of manhole change with temperature which could need to crack formation, a tilt
sensor is introduced to indicate whether the manhole can tilt. Also, a float sensor is
used to indicate when the water level goes beyond a certain level, in case of any alert
due to any of the parameters we send an SMS to an authority number as well as on the
IoT website. Also, all the parameters are continuously updated on the website.

**OBJECTIVE :**
The main aim of this project is to provide the user with real-time monitoring of the
manhole or sewer conditions using the latest technology from various sensors and
microcontrollers this will ultimately result in efficient safe operations of the sewer system
with minimal resources. The project consists of multiple sensors which sense
temperature, water level, poisonous gases, the tilt of the manhole cap and give this data
to a microcontroller which then based on the set parameters decides on what solution
needs to be done. For example, if the temperature or harmful gases are detected in the
manhole an alert is sent on the site using IoT which helps in taking the necessary
precautions. Without causing risk of lives. This whole process can be tracked and the
concerned authority can get real-time data on the condition of the manhole without
requiring much effort.
METHOD:
In order to build this project, we use the Atmega328p microcontroller. Which acts as the
brains of this project. The data from various sensors is accumulated to the microcontroller
which makes decisions based on set parameters. We use an ultrasonic sensor to tell us the
water level. Gas sensor to inform us about any poisonous gas in the system. We have multiple
other sensors like the tilt sensor which help us know if the cover of the manhole is open or if the
manhole is not properly closed. All the data from these sensors are then transferred to the
microcontroller which decides on what needs to be done. So, the main focus of this project is to
provide a system that monitors water level, atmospheric temperature, water flow, and toxic
gases. If drainage gets blocked and sewage water overflows, the manhole lid opens, it is
sensed by the sensors, and this data is sent to the corresponding managing station via
transmitter located in that area. Maintenance of manholes manually is tedious and dangerous
due to the poor environmental conditions inside. It is, therefore dangerous to go inside the
manholes for inspection of its current state. To solve all the problems related to underground
sanitation, a remote alarm system is necessary for transmitting data collected by the sensors set
inside the manhole to the managing station. This project uses Wireless Sensor Networks (WSN)
to implement this system. These nodes are composed of a controller, memory, transceiver, and
battery to supply power.

**COMPONENTS REQUIRED AND COSTING :**
1. Atmega 328p Micro controller (100 RS.)
2. DHT 11 Temp. and humidity sensor (100 RS.)
3. ESP 8266 Node MCU (300 RS.)
4. MQ6 Gas sensor (95 RS.)
5. MPU6050 Motion sensor (150 RS.)
6. Water level Float sensor (150 RS.)
7. PCB Breadboard (2X35 RS.)
8. Cable and connectors (50 RS.)

**FUTURE SCOPE :**
In the future, Smart cities infrastructure could be modified for intelligent communication
and management of traffic signals, street lights, transit applications, active lanes, and so
on. With the integration of smart devices in a city, infrastructure can make life in a city a
lot easier. Also further by using PLC controller and SCADA systems, drainage water can
be controlled, monitored and also this water can be used to irrigate plants, clean toilets,
etc. These PLC and SCADA systems can be used as a treatment system for drainage
water. Primarily, PLC controls the process of the sewage treatment plant and SCADA is
a remote terminal unit, which monitors and controls the entire area.

**CONCLUSION :**
The sensor unit automatically senses and updates the live values of the physical
parameters like temperature, humidity, water level and flow rate, blockages, and
manhole cap is open or closed through IoT. This makes the system smart and
automated. The deployment of Wireless Sensor Networks (WSN), helps in the
implementation of Smart cities in developing countries. This WSN can also be useful in
designing environmental monitoring systems, which helps in monitoring volcanic
activities, flood detectors, and other systems. By a small modification in the
implementation, this project can be used in agriculture fields or other environmental
fields to monitor and control the systems.
