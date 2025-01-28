# Partial_Function
 OOP Project: Partial Function Implementation

This repository showcases an Object-Oriented Programming (OOP) project focused on implementing an abstract base class PartialFunction. The class represents a partial function that transforms 32-bit integers and provides methods to check if the function is defined for a given input and to calculate its result.

The project includes concrete subclasses such as:

Partial Function by Criteria: Dynamically defines behavior based on a callable.
Max/Min of Partial Functions: Combines multiple partial functions to return the maximum or minimum result where defined.
Additionally, the program parses binary files (func.dat) to construct partial functions dynamically and supports two modes of operation:

Range Evaluation: Evaluates the function over a range of inputs.
On-Demand Evaluation: Lazily generates results for defined points.
