# Ch10-Simulator
 Core changes and assumptions:
 - I completed all exercises 12.45 - 12.48 objectives of moving methods
 into the superclass Animal in order to prepare to be able to add another
 animal subclass without having it have to instantiate or initialize its own
 variables and methods in order to implement it properly.
 
 - I added a subclass HoneyBadger of Animal, as my new animal addition to
 the simulation. I wanted this to simulate what happens when an aplha predator
 is introduced into a beta predator and small game prey environment. In which
 my assumnptions include that the alpha predator(HoneyBadger) slowly asserts
 dominance over the foxes and takes control of the environments food
 supply(Rabbit).
 - The main tweaks I had to make after superclass Animals inheritance methods,
 I had to adjust the breeding probabilities and intial spawn probabilities of
 the foxes and honey badgers, in which the honey badgers started in smaller
 numbers compared to the foxes as in reality honey badger populaitons are
 small to begin with when migrating to new territory and first feeding on
 beta predators such as, snakes, jackals, bobcats, and foxes. To which they
 then will typically thrive on the beta predators small game prey, including
 skunks, rabbits, birds, fish, etc . . .
