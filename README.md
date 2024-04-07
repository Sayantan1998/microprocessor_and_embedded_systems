This Repository Contains 4 different projects performed in the microprocessor and Embedded systems graduate-level Course at the University of Texas at Dallas.

The "accelerometer" folder contains two files. "accelerometer.ino" file contains the code that repeatedly reads 3D coordinates from a sensor, displays them on a screen, and sends them to a serial port. The "3d_plot.m" contains code for the device projection in the 3D plot in Matlab.

The "Joystick" folder contains "joystick.ino" which contains the code for a program controlling an LCD screen. It  includes libraries for the screen, fonts, and potentially other utilities. It defines functions to display text and numbers on the screen and handle errors. The code also includes an info screen that displays credits and other information.  The main loop continuously reads the joystick and displays the corresponding values on the seven-segment display.

The "msp432_timer_PWM" folder contains the "msp432_timer_PWM.ino" file, which displays rectangular pulse waves with different duty cycles. Pulse width modulation (PWM) represents a signal as a rectangular wave with a varying duty cycle. PWM is used to control the average power or amplitude delivered by an electrical signal by converting the signal into discrete parts. The width of the pulse, also called pulse width offset, is commonly proportional to the amplitude of the input signal.
The "MCU Timer.docx" contains the results and report of the experiment when the duty cycle is changed.


To run the code:-    
Download Energia IDE -> open the respective file -> check the port -> Build the project
