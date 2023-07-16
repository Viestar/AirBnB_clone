
![AirBnB](./assets/Screenshot%20from%202023-07-10%2014-59-47.png)
# Table of contents
TASK NUMBER | LINK TO TASK CODE | TASK DESCRIPTION | MERGED/AUTHORISED BY
----- | ------ | ----------
[0x00] | [README](./README.md) | Project Documentation | B
[0x00] | [Authors](./AUTHORS) | Project Authors | B
[0x01] | [Be pycodestyle compliant!](./) | Beautifully written code that passes the pycodestyle checks | B
[0x02] | [Unittests](./tests) | All files, classes, functions have been tested with unit tests, also in Non-interactive mode| B
[0x03] | [BaseModel](./models/base_model.py) | Defines all common attributes/methods for other classes  i.e ID, creation, update dates and a method to generate a dictionary representation of an instance | B
[0x04] | [Create BaseModel from dictionary](./models/base_model.py) | Re-creates an instance with the dictionary representation created in the previous task | B
[0x05] | [Store first object](./models/base_model.py) | Re-creates a BaseModel from another one by using a dictionary representation created in task 3, converted the dictionary representation to a JSON string. JSON is a standard representation of a data structure. With this format, humans can read and all programming languages have a JSON reader and writer. | B
[0x06] | [Console 0.0.1](./console.py) | Contains the entry point of the command interpreter using the Cmd class from the cmd module, defines the class HBNBCommand and sets the initial methods like quit, EOF and updates the prompt: | B
[0x07] | [Console 0.1](./console.py) | Added more methods to the console like updating details, showing details, destroing instances and more | B
[0x08] | [First User](./models/user.py) | Created the sub class User that inherits from the BAseModel with unique attribues like email, password, first and last names. | B
[0x09] | [More classes!](./models/) | Created the rest of the classes inheriting from BaseModel i.e Amenity, Place, City, State, etc | B
[0x10] | [Console 1.0](./models/engine/file_storage.py) | Updated file storage to manage correctly serialization and deserialization of all our new classes | B
[0x11] | [All instances by class name](./console.py) | Updated the console to retrieve all instances of a class by using: <class name>.all(). | B
[0x12] | [Count instances](./console.py) | Updated the console to retrieve all instances of a class by using: <class name>.count(). | B
[0x13] | [Show](./console.py) | Updated the console to retrieve all instances of a class on its ID: <class name>.show(<id>). | B
