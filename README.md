# ASP.NET Cheatsheet
ASP.NET Cheatsheet

## Table of Contents
* [MVC](#mvc)

## MVC
Model–view–controller (MVC) is an architectural pattern commonly used for developing user interfaces that divides an application into three interconnected parts. This is done to separate internal representations of information from the ways information is presented to and accepted from the user.

**Controller** accepts input and converts it to commands for the model or view. It is a class which contains actions and functions. A request to controller can be made by 
```url
http://web-address/controller-name/function-name
```

**Model** is responsible for managing the data of the application.

**View** means presentation of the model in a particular format. It can be output representation of information, such as a chart or a diagram. Multiple views of the same information are possible, such as a bar chart for management and a tabular view for accountants.
