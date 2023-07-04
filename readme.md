
# Comapring GML to JavaScript

**1. Objects and Classes:**

GameMaker Language (GML):
```gml
// Creating an object
obj_player = instance_create(x, y, obj_player);

// Defining a script associated with the object
script_init = scr_init;

// Defining variables in an object
player_health = 100;
player_speed = 5;

// Creating an instance of the object
var player = instance_create(x, y, obj_player);
```

JavaScript:
```javascript
// Creating a class
class Player {
  constructor(x, y) {
    this.x = x;
    this.y = y;
    this.health = 100;
    this.speed = 5;
  }
  
  // Method
  move() {
    // Code for moving the player
  }
}

// Creating an instance of the class
const player = new Player(x, y);
```

**2. Functions and Methods:**

GameMaker Language (GML):
```gml
// Defining a function
function addNumbers(num1, num2) {
  return num1 + num2;
}

// Calling the function
var result = addNumbers(5, 3);
```

JavaScript:
```javascript
// Defining a function
function addNumbers(num1, num2) {
  return num1 + num2;
}

// Calling the function
const result = addNumbers(5, 3);
```

**3. Inheritance:**

GameMaker Language (GML):
```gml
// Creating a parent object
obj_parent = instance_create(x, y, obj_parent);

// Creating a child object that inherits from the parent
obj_child = instance_create(x, y, obj_parent);
```

JavaScript:
```javascript
// Creating a parent class
class Parent {
  // Parent class code
}

// Creating a child class that extends the parent
class Child extends Parent {
  // Child class code
}
```

**4. Data Types:**

GameMaker Language (GML):
```gml
// Variable declaration and assignment
var player_name = "John";
var player_score = 100;
var player_position = 5.25;
```

JavaScript:
```javascript
// Variable declaration and assignment
let player_name = "John";
let player_score = 100;
let player_position = 5.25;
```

These examples provide a basic comparison of the concepts in GameMaker Language (GML) and JavaScript. It's important to note that the syntax and usage can vary depending on the specific versions of GameMaker Studio and JavaScript, as well as any frameworks or libraries being used.