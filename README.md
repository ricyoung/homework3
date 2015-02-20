# homework3
Due: Fri., Feb. 20, 2015, by midnight.
Purpose: This assignment is designed to:
• Introduce object-oriented programming in Ruby
• Practice basic programming solutions
Task: Write a program that implements a Book class that is used in a subsequent
Library class.
Discussion: A Library is a collection of Books. We can store Books in an Array
inside of a Library class (see starter code.)
A Library can add Books, check out individual Books, and list which Books are
checked out.
We define a class in Ruby as
class ClassName
. . .
end
and can instantiate a new object of that class with the statement
identifier = ClassName.new
A constructor is a special method that automatically executes each time an
object is instantiated. In the class definition, that method is called initialize,
and you treat it just as you would any other method.
Also, recall that instance variables in Ruby are normal variables that are available
throughout the entire class and are prefaced with the @ symbol (i.e., @books.)
Using the starter code below, craft a Book class that allows the program below
to function to completion. You shouldn’t have to alter the main code at all; simply
implement the Book class according to the Ruby programming language.
Criteria: Submissions must adhere to the criteria specified in the syllabus. Highlights
for this assignment include:
• Pay attention to the coding style and documentation guidelines in the syllabus.
• Use the following code to get your program started:
