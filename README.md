# RF Wireless Remote-Controlled Robot Car

An Arduino-Based Wireless Robotics Project

## Project Overview

The RF Wireless Remote-Controlled Robot Car is an educational robotics project designed to control a mobile robot wirelessly using a radio-frequency (RF) remote control.

The system receives commands from a wireless transmitter and uses a compatible receiver and motor-control circuit to drive the robot in different directions. This project demonstrates wireless communication, motor control, and embedded systems.

The exact operating logic depends on the Arduino program, RF modules, motor driver, and wiring used in the prototype.

## Components

* Arduino-compatible microcontroller board(s), if used
* RF transmitter and compatible RF receiver
* Robot car chassis
* DC geared motors
* Motor driver module (e.g., L298N, if used)
* Robot wheels
* Battery and suitable power supply
* Connecting wires
* Remote-control buttons or input switches

*Confirm the actual components against your hardware before finalizing this list.*

## Pin Connections

| Component                 | Arduino Pin                                  |
| ------------------------- | -------------------------------------------- |
| RF receiver data output   | Confirm from source code                     |
| Motor driver input pins   | Confirm from source code                     |
| Motor driver enable pins  | Confirm from source code, if used            |
| RF transmitter input pins | Confirm from transmitter code, if applicable |
| Power and ground          | According to the circuit                     |

The pin configuration varies with the RF modules, Arduino boards, and motor driver used. Update this table using the actual source code and circuit diagram.

## How It Works

1. The operator presses a button on the RF remote control.
2. The transmitter sends a wireless command.
3. The compatible RF receiver receives the transmitted signal.
4. The microcontroller interprets the received command.
5. The motor driver controls the DC motors according to the programmed direction.
6. The robot moves forward, backward, left, or right when the corresponding commands are supported by the code.

The available movements and response behaviour depend on the actual implementation.

## Software Requirements

* Arduino IDE, if the project uses Arduino
* Appropriate board support package
* Required RF communication library, if used
* Motor-control libraries, if required by the source code

## Setup Instructions

1. Install the Arduino IDE and the required libraries.
2. Assemble the robot chassis and mount the motors.
3. Connect the RF transmitter and receiver according to the verified circuit.
4. Connect the motor driver and motors.
5. Open the corresponding transmitter and receiver `.ino` files, if the project uses separate controllers.
6. Select the correct board and port for each controller.
7. Compile and upload the relevant sketches.
8. Power the circuit using suitable supplies.
9. Test the remote commands and confirm the robot's movement.

## Project Status

* **Source Code:[RC Robo Car Code.docx](https://github.com/user-attachments/files/33308801/RC.Robo.Car.Code.docx)

* **Circuit Diagram:<img width="2722" height="1536" alt="RC Robo Car Diagram" src="https://github.com/user-attachments/assets/5899ff36-5543-452e-8f36-04fb4165f7cb" />


* **Hardware Testing Video:https://youtube.com/shorts/jfCBv0P4ERI?feature=share
* **Hardware Testing:<img width="736" height="1307" alt="the ardino working and mechanism" src="https://github.com/user-attachments/assets/080f2926-fc85-47b5-8ad6-bcd7df91ec3d" />


### Suggested Repository Files

* `README.md`
* `robot_car_receiver.ino`
* `rf_remote_transmitter.ino` (if a separate transmitter controller is used)
* `images/circuit-diagram.png`
* `images/robot-car.jpg`
* `videos/robot-car-demo.mp4` (optional)

Use only filenames that match the files actually uploaded to the repository.

## Safety Note

Check the motor driver's current rating and the battery voltage before powering the robot. Do not drive motors directly from Arduino GPIO pins. Secure all wiring and test the robot on a clear surface.

## Author

**Imran Khan**

* GitHub: https://github.com/Imran-khan009
* Portfolio: https://sengrimrankhan.netlify.app

## License

Add an appropriate open-source license if you wish to define how others may use, modify, and distribute this project.
