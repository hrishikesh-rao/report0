# Level 0 Report

# Task 2: API

## Aim 

To understand how an API **works** and to create a small weather app using the API key of weathermap.

## Learning

### *What is an API?*

API or **Application Programming Interface** is the type of a connetion between the user interface and the system/server to enable processing of input and to communicate data

### *How to obtain an API key*?

APIs can be accessed using an API key from an API provider which is generally a long string of alphanumeric characters

## Steps taken
- Sign into the API provider website and obtain the API key(in this case weathermap api)
- Write code for a simple user interface using HTML and CSS.
- Insert your API key in the code
- Click on live server and in code editor(VSCode)
- The weatherapp is now created.

I did upload the file to my github
https://github.com/hrishikesh-rao/level0/blob/main/index.html


![](https://github.com/hrishikesh-rao/garbage/blob/main/Screenshot%20(109).png?raw=true)

![](https://github.com/hrishikesh-rao/garbage/blob/main/Screenshot%20(110).png?raw=true)
---
# TASK 3: Working with Github

## Aim

To rectify the error in the code and to pull a request

## Learning

Git is a **version control**, which means that you are able to store your already existing work safely and has previous work safely stored.
Github is such a **cloud-based** platform that lets you use git's power.
Also few commands specific to github like commit, push, fork, pull requests.

## Steps taken

- Forked the existing repo into a repo of my own.
- Corrected the error and committed it.
- Later did a pull request.

![](https://github.com/hrishikesh-rao/garbage/blob/main/Screenshot%20(121).png?raw=true)
---
# TASK 4: Command Line Interface on Ubuntu 

## Aim

To get familiar with **Linux commands** and make directories and concatenate them.

## Learning

I did learn the basic linux commands while doing this task and sad servers.

- **pwd**(print working directory): Prints the current directory in the next line.
- **cd**(change directory): Changes the directory into a given directory. Needs one argument.
- **ls**(list): Lists the given directory.
- **touch**: create a blank text file
- **mkdir**: makes a blank directory
- **seq**: generates sequence of numbers.
- **-f**: format options

This was fun doing!

![](https://github.com/hrishikesh-rao/level0/blob/main/cli1.jpg?raw=true)

![](https://github.com/hrishikesh-rao/level0/blob/main/cli2.jpg?raw=true)
---
# TASK5 : Build Your own Brain : Linear Regression

## Aim

To learn how to build the most simplest ML model, **Linear Regression**.

## Learning

### *What is Linear Regression*?

Maybe think of it as you are given a number of data points such that you cant fit a line through all of them, but you can find a best fit line, which has some small bit of extra distance from the given data point value to the line's value at that point.

So regression is all about reducing that error as far as possible, this can be used for prediction as it does do a pretty good job in predicting.

Regression is the most simplest Prediction algorithm.

### *So how does Linear Regression work?*

Inorder to truly understand, we must dive into the Math part of it.

Linear regression is a straight line.
A Straight lines equation is given by y=ωx+b

where ω= slope or in ML **weights**
      b= intercept or **bias**

So now lets assume we have been given loads of datapoints and we want to find the best fit line through all of these data points.

Lets given some temporary values to both ω and b as ω1 and b1 respectively.(Assuming that they are not the pair for the best fit line)

When we do plot the curve, we do observe that many data points fit well together, but some data points have a lot distance from the actual point to the value produced by the curve at that point.

So here comes something called as the Loss Function.

### Loss Function

Loss Function in its name itself means that we have a Function which can measure by how much magnitude we are going wrong in our predictions.
Loss function is an important metric in evaluating our models performance.

So there are two types of Loss functions

MSE(Mean-Squared-Error)-Most commonly used
MAE(Mean-Absolute-Error)

![](https://github.com/hrishikesh-rao/level0/blob/main/IMG_2857.jpeg?raw=true)

So why is mean squared error used commonly?
The reason is simple which will be explained below.

### Optimizer Algorithm

Optimizer Algorithm is used to reduce error.It is solely built on the loss function.

What does it optimize?
 It optimizes the parameters,i.e.ω and b in this case.

Let us go with the most simplest Optimiser algorithm, Gradient descent.

![](https://github.com/hrishikesh-rao/level0/blob/main/IMG_2858.jpeg?raw=true)

### Gradient Descent

So whenever we encounter a situation in maths that either we want the lowest point or the highest point our quick answer is running to calculus and using differentiation.

The same thing applies here, but with a little twist,Partial differentiation.

Since both ω and b change and are the parameters we differentiate the loss function with respect to both.

But since our loss function is either MSE or MAE, which one to choose?

MAE includes a modulus, taking its derivative will include us making two cases which will be cumbersome to solve,
Hence we use MSE.
Since error is to be reduced we consider the minima.

When defining the optimizer, we also have to submit a hyperparameter called the learning rate.
This learning rate defines how big your step is towards the minima.
We also have to define epochs. Epochs is the number of times we will go through the entire dataset while training the model.

![](https://github.com/hrishikesh-rao/level0/blob/main/IMG_2859.jpeg?raw=true)

If this is done properly, most of the math part comes to an end.

Lets say we had like multiple features, at that point we can use this equation to relate features and targets.(Note that the features and the targets must be related linearly.)
Since there are n features and 1 target, overall parameters are n+1.

This does conclude the theoretical aspect of a Linear regression model.

Here is the file for Linear Regression using Sci-kit Learn.
[Click here](https://github.com/hrishikesh-rao/report0/blob/main/LR%20(2).ipynb)
---
# TASK 6: The Matrix Puzzle

## Aim 

To solve the puzzle using NumPy and Matplotlib.pyplot and to reveal the image.

## Learning

### *What are NumPy and Matplotlib?*

**NumPy** is a library/framework of python which is used for array manipulation,reshaping, resizing and for transposing.

**Matplotlib** is a library/framework of python which is used to plot graphs and waves, using plot functions like plt.imshow(),plt.show etc.
matplotlib also has features for labelling X and Y axes.

Both the libraries are important for ***Machine Learning***, as **Numpy** is used widely for array manipulations, and **Matplotlib** is used for plotting graphs

This task is essential as NumPy and Matplotlib are the building blocks in learning ML.

![](https://github.com/hrishikesh-rao/level0/blob/main/Screenshot%20(123).png?raw=true)
---
# TASK 8: Writing Resource Article using Markdown

Here's a resource article I have written about music.
[Click here](https://github.com/hrishikesh-rao/report0/blob/main/music.md)
---
# TASK9 : Tinkercad

## Aim
To learn the working the tinkercad and to make a simulation of the working of an ultrasonic sensor.

## Learning

Tinkercad is a cool website by which we can do simulation of our circuits and demonstrate the simulation without actually doing the assembly of the components.

### Components required

![](https://github.com/hrishikesh-rao/garbage/blob/main/Screenshot%20(119).png?raw=true)


The servo motor is only applicable only when the setup is done in real life when the sensor is glued to the motor, it provides a semicircular/circular FOV for motion detection.

[View my simulation](https://www.tinkercad.com/things/lTkyf2CoGuk-tinkercad-task)
---
# TASK 10: Speed control of DC motor

## Aim

To study the working of the L298N motor driver and to control the speed of the DC motor using a potentiometer.

## Learning

### Understanding Motor Control 

Two Main key concepts should be known:

- **H-bridge Circuit**- Allows the control of direction of motor's **rotation**.

- **PWM**- Stands for pulse width modulation, helps controlling the **speed** of DC motor

#### *What exactly is the H-Bridge circuit?*

H-Bridge circuit is such a circuit which uses 4 switches inorder to switch direction of current across a load.
Here the load is the DC Motor.

Heres the H-Bridge diagram

![](https://github.com/hrishikesh-rao/garbage/raw/main/1585313613715-h-bridge.gif)

#### *What exactly is PWM?*

We know that speed of the motor is directly proportional to the magnitude of current flowing across it.
So once the value of voltage is set, the current flowing will be set constant.
But what if we wish to change the speed of motor?
That is where a PWM comes into play.
PWM depends on the duty cycle, based on it we can change the magnitude of the speed.

--- 
### Structure of L298N motor driver

**L298N** is a dual motor driver i.e can control two motors at once.

It has a large heat sink, a big chip.
Its characteristics are high-voltage,high current, does amplification of current, recieves low current from arduino and amplifies to high current and high voltage for motors to operate.

L298N has two H-bridges as it is a dual motor driver.

Power ranges of L298N includes 5V to 46V and can supply upto 2A of continuous current supply.

Pinout of L298N motor driver
![](https://github.com/hrishikesh-rao/garbage/blob/main/Screenshot%20(111).png?raw=true)


Varying the potentiometer, we can control the speed of DC motor.

![](https://github.com/hrishikesh-rao/level0/blob/main/WhatsApp%20Image%202025-09-09%20at%2020.45.06_04a90862.jpg?raw=true)
---
# TASK 11: LED Toggle using ESP-32

## Aim

To control the on/off action of two led bulvs using ESP32

## Learning

ESP-32 is a widely used microcontroller board for IoT projects as it provides a wide range of functionality like bluetooth and WiFi connection. It has a very highclock rate of 240GHz which makes it have a relatively high data processing speed.

I referred to this site reading about esp32(highly recommend it!)
[Click here](https://www.nabto.com/guide-to-iot-esp-32)

Pinout of esp32

![](https://lastminuteengineers.com/wp-content/uploads/iot/ESP32-Pinout.png?raw=true)

esp32 has many pins namely
- power pins for supply purposes.
- 34 gpios but some have restrictions(GPIO stands for general purpose input output.)
- sda and scl pins for usage of a screen/monitor.
- pwm pins for led/motor control.
- adc and dac pins

Components required: esp32,resistor(220ohms,qty-2), breadboard, jumper wires,led(qty-2).

# Steps Taken

- Did the circuit connections.
- Wrote and compiled the code in arduino ide for esp32 dev kit.
- In serial monitor obtained the ip of the webserver and opened the webserver.
- Used the buttons to on/off the two led.

Also whilst doing i realised that the WiFi to which esp 32 is connected to, must be used to run the webserver in laptop or mobile.

![](https://github.com/hrishikesh-rao/garbage/blob/main/esp32.jpg?raw=true)

![](https://github.com/hrishikesh-rao/garbage/blob/main/webserver.jpg?raw=true)
---
# TASK 12: Soldering Prerequisites

## Aim

To learn how to solder and desolder.

## Learning

Soldering is a pretty important process when anyone is dealing with joining electronic components together.
One of the most extensively used process is fairly simple if done with great precaution.
Desoldering is the exact opposite of soldering, which is to remove the components, it usually done by just introducing the soldering iron at the soldered spot.

Key parts of a soldering station.
- Soldering iron - Pen like structure which heats up to nearly 900 Fahreinheit when 120 V AC supply is connected.The tip of the soldering iron has a **spot** where the solder melts.
- Solder -  It is the main metallic alloy part which melts to form a filament when the tip of the soldering iron is made in contact. Usually made up of a Lead-Tin alloy.
- Soldering sponge- When excess of the oxidated solder gets stuck to the tip of soldering iron after soldering, it is cleaned using a soldering sponge. A brass sponge is used.
- Soldering Stand - It is a place to store the soldering iron. It prevents the tip of soldering iron melting other materials.
- Soldering paste - It  is a mixture of fine metal solder powder and flux, providing both the solder material and the necessary cleaning agent.

Make sure not to burn yourself.
![](https://github.com/hrishikesh-rao/garbage/blob/main/solder1.jpg?raw=true)

![](https://github.com/hrishikesh-rao/garbage/blob/main/solder2.jpg?raw=true)

---
# TASK14: Karnaugh Maps and Deriving Logic Circuits

## Aim 

To make an alarm based on the four cases of the door and key combination using **K-Maps**

## Learning

So essentially K-Maps are used to simplify and derive logic circuits. When a long expression of logic circuits of n combination odvariables are given, we can easily simplify the circuit and obtain the output.
K-Maps are simplified by grouping terms into two or forming octets or quads.

## Steps taken

- I first started by writing the truth table for the conditions.
- Later did the K-Map to find my logic circuit.
![](https://github.com/hrishikesh-rao/garbage/blob/main/IMG-20250907-WA0001%5B1%5D.jpg?raw=true)
- I also did an online simulation of how the logic circuit actually works.
https://youtu.be/h5O9i5HqFPI
---
# TASK 15: Active Participation

I did attend the Tech fest called **UTSAV** in bms. I participated in an event called as **yodhaverse**
Heres the certificate

![](https://github.com/hrishikesh-rao/garbage/blob/main/active.jpg?raw=true)
---
# TASK 18: Sad servers - "Like LeetCode for Linux"

## Aim:

To solve the given murder and to figure the criminal

## Learning

Exact functions and usage of linux commands in terminal.

**pwd**(print working directory): Prints the current directory in the next line.
**cd**(change directory): Changes the directory into a given directory. Needs one argument.
**ls**(list): Lists the given directory.
**grep** : searches any given word in the files.Requires two arguments, one is the word and one more the location.
**head**: Used to display the first certain lines in the file.
**-n**: Used to limit printing.
**cat**: used to display files.
**echo**: used to input text into a file.

After a lot of times trying i finally did find the solution.

![](https://github.com/hrishikesh-rao/level0/blob/main/Screenshot%20(101).png?raw=true)
---
# Domain Specific Tasks.
---
# TASK 20: Jupyter Notebook

## Aim 

To familiarise the ui of the jupyter notebook and to do the give task

## Learning

**Jupyter notebook** is such a tool where coding becomes simple,you can use it for explaining code as it cells for markdown, and running the individual cells helps understanding code.

Doing this task was kinda fun.

Heres the link to my mini report:
[Click here](https://github.com/hrishikesh-rao/garbage/blob/main/scratch.ipynb)
---

# TASK 21: Task 21: Watch & Reflect – Intro to Machine Learning.

[Here's the link to my resource article](https://github.com/hrishikesh-rao/report0/blob/main/vid.md)
