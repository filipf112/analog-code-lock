# Analog code lock project
Project of analog code lock with circuit design and PCB design

## System assumptions and operation
The project's assumption was to construct an analog code lock. The circuit was based on the digital circuit CD4017, which operates by changing the output after each pulse at the CLK input. Eight buttons were used to create a sequence forming a password, four of which were responsible for the password, while the rest reset the circuit upon being pressed. Pressing the correct buttons in the established order activates the LED and relay RY1. To secure the circuit, diodes and resistors were used, and capacitors were installed to stabilize the current flowing in the circuit.

## Schematic
Below is the schematic of the project created in the Eagle program, along with the names and values of the components.
![Schematic](https://github.com/filipf112/analog-code-lock/blob/main/Images/schematic.jpg)

## Simulation
To conduct the simulation, the SimulIDE program was used. As seen, upon pressing all the buttons forming the password in the correct sequence, the LED lights up, and the relay begins to operate.
![Simulation](https://github.com/filipf112/analog-code-lock/blob/main/Images/simulation.jpg)

## PCB Design
Based on the schematic created in the Eagle program, the PCB layout was generated.
![PCB Design](https://github.com/filipf112/analog-code-lock/blob/main/Images/PCB.jpg)

## Final project
![Final project](https://github.com/filipf112/analog-code-lock/blob/main/Images/Final.jpg)
