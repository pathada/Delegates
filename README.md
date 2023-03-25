# Delegates
for practise purpose


Delegates in Swift are a design pattern used to facilitate communication between two objects or components of an application. 
In this pattern, one object delegates responsibility for a particular task to another object.

In Swift, delegates are implemented using protocols. 
A protocol defines a set of methods and properties that a class or structure can implement to provide a specific functionality.

The object that delegates responsibility is usually referred to as the delegating object, while the object that handles the task is referred to as the delegate. 
The delegate object implements the protocol methods and provides the implementation details for the task it is responsible for.

Delegates are commonly used in UIKit framework for handling events such as button taps, table view selections, and text field editing. 
By using delegates, view controllers can delegate the responsibility of handling these events to other objects, allowing for better separation of concerns and more modular code.
