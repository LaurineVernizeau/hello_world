# Documentation

### Table of content
* Material
* Base of programming with Arduino IDE 

## Material

* **ESP32 :**
<br>The ESP 32 is a microcontroller. A microcontroller is an integrated circuit that brings together 4 essential elements: a processor, memory and peripheral units and input-
output interfaces.
<br>This microcontroller is programmable: with your computer you will be able to control the inputs and outputs and interact with the outside world.

* **BREADBOARD:**
<br>A breaboard is a board that allows you to connect all of your elements without soldering.
<br>For this, different locations are connected together (as illustrated below).

## Base of programming with Arduini IDE 
<br>The Arduino IDE tool is an integrated development environment, it is the interface that allows you to import code into the EPS32 microcontroller.

## Start
<br>The code has two main functions: 
<br> *setup()* : the code written in this function will only be executed once.
<br> *loop()* : the code written in this function will be executed repeatedly as long as the ESP32 is powered.

## Comments 
<br> The microcontroller executes the instructions from top to bottom. It is possible to add comments in order to make the code more readable. These comments will not be read by 
the microcontroller. There are two ways to add comments:

## Function 
<br>The *setup()* and *loop()* functions are obligatory for the proper functioning of the code. However, other functions can be created. These functions can be called later in 
the two main functions.

## Tools used functions
### Variable : 
<br>They can be of different types:
<br>There are other data e.g. for text.
<br> Some variables are only defined in the function. Other variables can be defined throughout the code, these are the global variables. They must be defined outside of the functions.

### Operation : 
<br>Operators are used to apply operations to variables.
Symol | Meaning
------------ | -------------
+| addition
/| division

### Condition :
#### if loop : 
<br>The structure of the conditions makes it possible to initiate different instructions according to different conditions. As mentioned earlier, the comparison returns true or 
false. This result is used for the if structure.
If the condition is true the instructions are executed, otherwise the following condition is tested. If none of these conditions is true, we execute the instructions of *else*.

#### Logical connectors :

A comparison returns a boolean, that is, either true or false.
For example, 5 > 3 returns true and 5 < 3 returns false.
There are several comparators:
Symol | Meaning
------------ | -------------
<| lower
<= | lower or equal
\> | superior
\>= | superior or equal
 == | equal
!=| different 

A condition can be made up of several comparisons, thanks to the logical connectors:
Symol | Meaning
------------ | -------------
 && | and
 &#124; &#124; | or

<br>*exemple:* 
<br> Here, *a* is not between 2 and 5 excluded. Thus, instructions 2 will be executed.

### * For loop : 
he FOR loop makes it possible to carry out a defined number of times of instructions.

A variable initialized to 0 is defined. The latter will be incremented by 1 each time it passes through the loop and the instructions inside the loop are executed. When the variable reaches the value of a, we exit the for loop and the rest of the code is executed.
*exemple:*
<br>Here, we add: 0 + 1 + 2 + 3 + 4. So, after the loop, the variable sum is equal to 10.

### Predefined functions
- **pinMode**(*number_GPIO*,*mode*);
<br> Used to indicate whether the GPIO is defined as : 
<br> -> output mode: *OUTPUT* (ESP32 sends information) 
<br> -> input mode : *INPUT* (ESP32 receives information).
- **delay**(*duration*);
<br>Allows you to enter a time delay with *duration* in ms.
- **digitalWrite**(*number_GPIO*,*level*);
<br> Used to power the GPIO in the high state: *HIGH*, otherwise the GPIO is in the low state: *LOW*.
- **Serial.println**("*text*");
<br>Display text on the serial monitor.
<br>
<br>You find more predefined function int the ESP32 documentation online. 

### Compile you code 
<br>This tab allows you to check and upload the code to the microcontroller.
<br>This tab opens the serial monitor. It allows you to "communicate" with the ESP32, you can then display a text or a variable.
<br>Once the code has been verified and uploaded, if everything has worked, the following message should appear.
