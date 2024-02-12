# Welcome to the AirBnB clone project!



This project aims to replicate the basic functionalities of airbnb's backend system through a command-line interface(CLI) in python.
The CLI allows users to interact with the system by creating, updating,deleting and querying various objects such as users, places, review and more.

## installtion:
1- Clone the repo to your local machine:
 

 > git clone <repo_url>


 2- Navigateto the project directory:

 > cd <AirBnB_clone>

 3-Ensure you have  python3.x installed on your system

 4- Run the 'console.py' file to start the command line interface:
 >python3 console.py

 ## usage:
 Once the console is running, you can use the following commands:

 1- create:Create a new instance of a class:
 > create <class_name>

2-show: Show the string representation of an instance:
> show <class_name> <instance_id>

3-destroy:Destroy instance:
> destroy <class_name> <instance_id>

4-all: Show all instance of a class or all instance in general
> all <class_name>
> all

5-update: Update an instance:
>update <class_name> <instance_id> <attribute_name> "<new_value>"
6- count: Retrieve the number of instance of a class
>count <class_name>
quit or EOF: Exit the console
>quit
>EOF

## Example of Usage:
~~~
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
~~~

## Files:

### 1.base_model.py:
Define the 'basemodel' class which serves as the base class for all others classes in the application, it includes methods for initiliaztion, string representation,saving to JSON, and conversion to dictionary format.
 ### 2.file_storage.py:
 Provides a class for serializing instances into JSON file and deserializing JSON files to instances, it includes methods for adding objects to storage, saving storage to a file, reloading data from a file, and more.
 ### 3.console.py:
 Implements the command-line interface(CLI) for interacting with airbnb clone system, users can create, show , update, destroy and list instances of varuios classes using this CLI.


 ## Authors:
Mohamed Suliman (moealsir)

Mohamed saifeldin
