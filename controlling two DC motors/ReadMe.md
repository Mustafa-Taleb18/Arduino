#### **The objective**:
Desgining a system to control the speed and the direction of two high current DC motor independently.

#### **Requarements**:

* Aduino Uno
* buttons (4)
* L298 motor driver 
* DC motor (2)

#### **The explenation**:

There are two types of DC motors: The first is **Brushed DC**, it's The cheapest and samplest motor, and the seconde is **Brushless DC**, it's higher efficiency, but more complicated.
Usually uses in toys and moving vehicles like *Wheeled Mobile Robots (WMR)*. We use two motors to simulate the control of Wheeled Mobile Robots, each motor is control the wheel of one side.

The speed controlling is implement by *software*, but ofcourse we can use a variable resistor to control the speed.

There are two functions of L298 motor driver, the first is to operate the motor in two direction and the seconde is to oprate the motor that consumed more current than Arduino output.
