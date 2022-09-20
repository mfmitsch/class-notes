# Object Oriented Programming

## The idea is to marry state and behavior

'''vb
Dim myname as String
Set myName = "Jeff"

MsgBox(UCase(myName))
'''

'''csharp
var myName = "Jeff";
myName = myName.ToUpper();
'''

Things that you are most likely to do with a type are attached to that type

## objects have:

### State
variables that the object "owns"
In .NET state is in class level variables we use the term Fields for these

### Behavior
code that can be invoked that has something to do with the data (state) owned by that object.
In .Net the behavior is methods.
Constructors, Properites and Events.

## Example
I have an object that represents a bank account
### state 
the bank account has a current balance
