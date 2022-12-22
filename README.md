
# Detecting-Forest-Fires

<h1><b>Week 1</b></h1>
<h2>Study Resources</h2>
<h3> For this week you will be brushing up your <b>Python</b> basics</h3>
For this week,the <a href='https://scrimba.com/learn/python'>scrimba course</a> is sufficient for the python part.
 <h2>Assignment for Week 1</h2>
Create a Bus Class and a Car Class which inherit the properties of the Vehicle Class given in vehicle.py given below. 
Bus and Car should have seating_capacity of 25 and 5 people respectively. Additionally, the bus should have a standing_capacity member of 15 people and Car has a ID as member variable.


Tasks:
Create two instances of the Car class with unique car IDs and one of the Bus Class.

Your job is to have 0 passengers in all 3 of these vehicles initially and it should keep a track of the number of passengers.

The program asks for user input and responds to the following character inputs:

A: The user wants a seat in a car. If alloted return "Alloted seat in car" and gives the ID

B: The user wants a seat in Bus. If allotted a space in the bus, output should specify whether a standing or sitting space was allotted. Sitting space must be filled before any standing seats are allotted.

C: Reduce exactly one passenger at random (Bernoulli Trial with 60% chance a person is removed from the bus and 20% from each car) from either the bus or the car. If you could not remove a passenger return that no passenger was removed. If removed a passenger specify vehicle and ID(if any). Assume Standing passengers are removed before sitting passengers always

Any other command: Exit code

class Vehicle: 
    def _init_(self, name, max_speed, mileage):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage

    def seating_capacity(self, capacity):
        return f"The seating capacity of a {self.name} is {capacity} passengers"
        
Optional: Receive and ID from the user who uses "A" command and store which vehicle they are in, ID, etc. Which data structure will you use for this? That way, when a random user is removed, you can even identify exactly which user was removed rather than simply counting the number of passengers.
Hint for this: simply have a member variable denoting the number of passengers in each vehicle and manipulate that using member functions (will it be easier to use non-member functions directly?)
  <h1> End of Week 1 </h1>
  <h2> Deadline: 25th of December </h2>
