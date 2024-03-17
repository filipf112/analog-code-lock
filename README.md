# Analog code lock project
Project of analog code lock with circuit design and PCB design
1. System assumptions and operation
The project's assumption was to construct an analog code lock. The circuit was based on the digital circuit CD4017, which operates by changing the output after each pulse at the CLK input. Eight buttons were used to create a sequence forming a password, four of which were responsible for the password, while the rest reset the circuit upon being pressed. Pressing the correct buttons in the established order activates the LED and relay RY1. To secure the circuit, diodes and resistors were used, and capacitors were installed to stabilize the current flowing in the circuit.

2. Simulation
To conduct the simulation, the SimulIDE program was used. As seen, upon pressing all the buttons forming the password in the correct sequence, the LED lights up, and the relay begins to operate.

![alt text](https://github.com/filipf112/analog-code-lock/blob/main/Images/schematic.jpg)
