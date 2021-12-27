Nested To do list
--

This represents another standard Front-end kata: make a to do list, but allow nested sub-lists

There's a few things about the problem that make this interesting:
* (again) How to represent a data model: nested data is a little trickier than it looks
* The data model is infinitely nestable, but Alpine does not allow recursive layouts. As it has an 
emphasis on simplicity, this is quite understandable.
