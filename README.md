# Door-Watcher
Highly available, low cost, real time door monitoring system

## Main Idea
You have a door (your house's / apartment main door) and you want to monitor the door's status when you're not at home to see if someone breaks in without you being aware of that. 

This system is composed of a hardware component mounted on the door, a cloud VM that stores and processed all the data that is sent by the hardware and an iOS application that shows you in realtime what happens with the door.

The key targets of this system are: to be reliable (avoid false positives), real-time, extensible and low-cost.

## Tools needed
* 1 x Raspberry PI 3 model B
* A Wi-Fi network used by the Raspberry to get Internet access (could be the home network)
* 1 x Magnetic [door switch](https://www.robofun.ro/magnetic-door-switch-set)
* [Wires](https://www.robofun.ro/fire-conexiune-mama-mama-10-bucati-10cm?search=fire)
* A Mac, X-Code installed and an iPhone

## Architecture

![alt text](Images/DoorWatcherArchitecture.png "Architecture")

## Embedded code

## IOS app architecture
