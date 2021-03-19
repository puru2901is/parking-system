# parking-system

USE CASE Description:
1. Park the vehicle according to the slot size available.
2. Unpack a vehicle and 
3. calculate the charges according to vehicle and number od hours.


Trigger:
1. Vehicle entrying the parking lot
2. Vehicle existing the parking lot

Actors:
1. Vehicle - two-wheeler, four wheeler and eight wheeler
2. Parking slot - two-wheeler slot(TWS), four wheeler slot(FWS) and eight wheeler slot(EWS)
3. Patking lot
4. Parking Ticket

Preconditions:
1. Number of parking slot are categorized according to the size

Goals:
1. Find suitable parking slot for the Vehicle

Steps of Execution:
Parking
1. Vehicle reaches parking lot
2. Parking slot is allocated according to vehicle and availibilty
3. Parking ticket is generated with in time

Unparking
1. Vehicle is identified
2. Cost is calculated according to the time spent and vehicle time
