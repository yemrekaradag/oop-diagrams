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
