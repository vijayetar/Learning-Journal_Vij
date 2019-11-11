# Functions, Methods and Objects page 106-144
## Objects in Literal Notation:
Example:
- var hotel = {
  name:'Quay',
  rooms: 40,
  booked: 25,
  checkAvailability = function() {return this.rooms - this.booked;}
};
- the contents of the object are retrieved using the dot notation e.g. hotel.name where period is the member operator and property is the member of the object
- it can also be retrieved using square brackets for e.g. hote['name']

- retrieve information by assigning them to variables.

---
## Objects in Constructor Notation:
Example: 

- var hotel = new Object();
hotel.name = 'Quay';
hotel.rooms = 40;
hotel.booked = 25;
hotel.checkAvailability = function () {
  return this.rooms - this.booked;
};
- *Key to rememeber is it uses all semi-colon in all lines including after curly braces*

- delete using "delete hotel.name;"
- or clear value by assigning to blank string

---
## Create many objects using Constructor Notation

Example: 
- function Hotel(name, rooms, booked) {
  this.name = name;
  this.rooms = rooms;
  this.booked = boooked;
  this.checkAvailability = function () { this.rooms - this.booked;};
}

- *Key features is use of **this** keyword and use of **capital** letter to define the constructor function. You will then have to use **new** keyword to call the new function to create an **instances** ofthe object. The properties of each object are given as **arguments** to the function and then **initialized** to a variable*

- var quayHotel = new Hotel ('Quay', 40, 25);
- var parkHotel = new Hotel('Park', 120, 77);





[Return to homepage](README.md)