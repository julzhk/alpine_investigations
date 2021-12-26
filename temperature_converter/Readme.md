Convert from a variety of temperature scales
--

This represents a standard Front-end kata: make a calculator for converting from a variety of 
temperature scales.

There's a few things about the problem that make this interesting:
* How to represent a data model: In this case we have three temperatures rather than a single reference
temperature and just change the way it's represented
* Having multiple inputs that are also outputs. The 2-way binding can be tricky if it's got to change other input fields
too.
* Validation: You can't get lower than zero Kelvin. There's no upper limit, but there is absolute zero
