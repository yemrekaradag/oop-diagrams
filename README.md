# University Management System:

I designed a system that represents the organizational structure of a university.
Here’s what I implemented:

The university has classrooms, work offices, and departments.
Each department has its own offices.
The university employs staff members, who can be either professors or administrative personnel.
Every staff member works in an office.

I created a Class Diagram to represent this system.

Note: There was no need to specify the attributes or behaviors of the classes.

# Zoo Management System

In this project, I designed a system to track information about animals in a zoo.

The animals are categorized into groups such as:

Equines (e.g., horses, zebras, donkeys)
Felines (e.g., tigers, lions)
Rodents (e.g., rats, beavers)

Most of the information stored about the animals is common across all groups, such as species name, weight, and age.

The system must also be able to:

Retrieve the dosage of specific medications for each animal → getDosage()
Calculate the feeding schedule for each animal → getFeedSchedule()
However, the logic for these functions varies depending on the animal group. For instance, the feeding schedule algorithm for horses differs from that of tigers.
To handle this behavior effectively, I designed a Class Diagram using the concept of polymorphism, allowing each animal group to implement its own version of these methods.

# Flight Management System

In this project, I designed a system for managing flights and pilots.

The system includes the following concepts:

Airline companies operate flights, and each airline has a unique identifier.
Each airline owns aircraft of different types.
Aircraft can either be operational or under maintenance.
Every flight has a unique ID, a departure and arrival airport, as well as departure and arrival times.
Each flight is operated by a pilot and a co-pilot, who are responsible for flying the aircraft.
Airports have unique identifiers and names.
Pilots are employed by airline companies, and each pilot has a specific experience level.
Each aircraft type may require a certain number of pilots to operate.

To represent this structure, I designed a Class Diagram that models the relationships between airlines, aircraft, pilots, and flights.

# Online Movie Rental System

In this project, I designed a system for an online movie application where users can buy or rent films.

The system includes the following main features:

Movies can be listed and sorted within the application.
Users can subscribe to the platform.
To activate a subscription, users purchase credits through the system.
Only subscribed users can rent movies, and the corresponding credit amount for each rental is deducted from their account.
Both regular users and subscribers can purchase movies.
If a movie is not currently available, users can submit a request for it.

To represent this functionality, I created a Class Diagram that models the relationships between users, subscriptions, credits, and movies.

# Elevator System

In this project, I designed a Class Diagram based on the following problem statement.

While modeling the system, I applied Object-Oriented Programming (OOP) principles and class relationships, including Encapsulation, Inheritance, Polymorphism, and Abstraction.

## Project Description

Kodluyoruz Insurance Company plans to construct a 12-story office building and equip it with the latest elevator technology. The company requested the development of a software simulator to model elevator operations and evaluate whether the elevator system can efficiently handle building traffic.
The building will contain five elevators, each capable of serving all 12 floors. Every elevator can carry approximately six adult passengers. They are designed to be energy-efficient, operating only when necessary.

Each elevator has:

Its own door, floor indicator light, and control panel.
The control panel includes destination buttons, door open/close buttons, and an emergency alarm button.

Each floor of the building includes:

Five elevator doors (one for each elevator shaft).
A arrival bell for each door that rings when an elevator arrives.
A signal light above each door that indicates the elevator’s arrival and direction of movement.
Three sets of elevator call buttons (for up and down requests).
When a person presses an appropriate call button (up or down), a scheduler program assigns one of the five elevators to respond to the request.
After entering the elevator, the passenger presses one or more destination buttons to select their target floors.

As the elevator moves between floors:

An indicator light inside the elevator updates passengers on the elevator’s current position.
When the elevator arrives at a floor, the indicator light above the external door illuminates, and the arrival bell rings.
The doors on both sides automatically open for a set period, allowing passengers to enter or exit.
The simulator uses a clock to simulate real-time passage and logs all events with timestamps.
A random number generator is used to create passengers and assign their departure and destination floors within the simulation.

I modeled this entire scenario using OOP concepts, defining classes such as Elevator, Floor, Door, ControlPanel, Passenger, Scheduler, and Simulator, each responsible for encapsulating specific system behaviors.
