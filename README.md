# inheritance
Object Oriented Programming is a paradigm of programming in which we try to model our own types/objects. For example we want to write a program for representing a "player" in a game, a player has very specific attributes such as health, attacks, level etc. and a "player" can perform some tasks such as attack, jump, move etc. this can be easily represented using functions and some data structure to store player's attributes. But let say now we want it to be multi-player game, so there would be many such "players" now it becomes a bit more difficult to manage such code, complexity exponentially increases. What if we could bundle together all the code for "Player" together? The above problem can be easily solved using Classes and objects, considering the above example we can create a "Player" Class, a blueprint to define a player and then we can instantiate that class to get as many players as we want!

Some Terminology:
Class: Class can be thought of as a blueprint which can be reused to create something multiple times. For example a class to represent an Employee in a company, where we'll have to define some basic properties that all employee's share such as name, age, salary, position etc in a class and then that class can be used to create multiple objects.
Objects: An object is a instance of a class. To understand we can take an example: Let say we declare a class Employee, now each object of this class will represent a different employee. Objects can be given some initial state using something called constructor which we'll see next.
Constructor: A constructor is used to give objects some initial state/value which is unique to that object. To extend upon the above example where we had an Employee class, Each employee has some predefined characteristics such as name, age, salary etc. we can use a constructor to start off the state of employee object with some specified values for age, name, salary etc.
Class Specifiers:
public : members can be accessed from outside the class
private : members cannot be accessed or viewed from outside the class.
protected : members cannot be accessed outside of class, they can be accessed in inherited class.
