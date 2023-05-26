ALU-AirBnB clone
Description
 Airbnb, as in “Air Bed and Breakfast,” is a service that lets property owners rent out their spaces to travelers looking for a place to stay. Travelers can rent a space for multiple people to share, a shared space with private rooms, or the entire property for themselves.
 Project to be done in teams of 2 people (Obedine-Flore and Morioh Onyonyi)
 Installation
 Clone this repository: git clone "https://github.com/FrankOnyemaOrji/AirBnB_clone.git"
Access AirBnb directory: cd AirBnB_clone
Run hbnb(interactively): ./console and enter command
Run hbnb(non-interactively): echo "<command>" | ./console.py
Relevant Files And Directories
models: directory will contain all classes used for the entire project. A class, called “model” in a OOP * project is the representation of an object/instance.
tests: directory will contain all unit tests.
console.py: file is the entry point of our command interpreter.
models/base_model.py: file is the base class of all our models. It contains common elements: .attributes: id, created_at and updated_at .methods: save() and to_json()
models/engine: directory will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py.
Using the Console
Run the console: ./console.py
Quit the console: (hbnb) quit
Display the help for a command: (hbnb) help
Show an object: (hbnb) show or (hbnb) .show()
Destroy an object: (hbnb) destroy or (hbnb) .destroy()
Show all objects, or all instances of a class: (hbnb) all or (hbnb) all
Update an attribute of an object: (hbnb) update "" or (hbnb) .update(, , "")
Examples

Interactive mode
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
===================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
  Non-interactive mode:
  $ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
==================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
==================================
EOF  help  quit
(hbnb) 
$
  Authors
  
Obedine-Flore
Morioh Onyonyi
Ziga Larissa
