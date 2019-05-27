# Park Smart With Astro ( OneM2M Hackathon)

An interesting prototype to solve the parking problem by the use of IOT.  

### Technical Specs
    * NodeJS
    * Android
    * NodeMCU Board
    * OneM2M Dashboard

# Description

The Proximity Sensors are placed in the parking lots to collect the data of the existing parked vehicles. These sensors are connected to NodeMCU boards which upload data to OneM2M platform. 

In NodeJS the data is extracted to comprehend the trend in parking area occupancy from OneM2M dashboard. 
The Android app communicates with NodeJS to fetch the metadata and to book an available spot.

1) The App displays the available parking spots in the vicinity. 
2) User clicks on "Book the spot"
3) Parking Spot displays "Reserved" on its display, and a cylindrical bar gets raised from the ground via motor. If the spot hasn't been reserved, any person can park the car. This gets reflected in the app in no time.
4) When the user arrives, he clicks on "Park", the cylinder goes down, he parks it. Message "In Use" is displayed.
5) The parking fee can be prepay or calculated on the time the car has been parked.
6) When the car leaves the "Available" will be displayed. 
