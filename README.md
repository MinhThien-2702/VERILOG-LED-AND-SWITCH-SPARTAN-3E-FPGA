# VERILOG-LED-AND-SWITCH-SPARTAN-3E-FPGA

## Project Description
This project demonstrates how to use Verilog to control LEDs and read switch inputs on the Spartan 3E FPGA development board. The primary objective is to create a system where the state of LEDs can be controlled based on the input from switches. This showcases basic digital design principles and FPGA interfacing techniques.

The project involves writing Verilog code to control LEDs based on switch inputs, simulating the design to ensure correct functionality, and deploying the design onto the Spartan 3E FPGA. It includes the use of FPGA I/O pins to interface with LEDs and switches.

## Features
- **LED Control**: Implement logic to turn LEDs on and off based on switch inputs.
- **Switch Input Handling**: Read the state of switches and use this information to control the LEDs.
- **FPGA Interfacing**: Demonstrates how to connect and control LEDs and switches using Verilog and the Spartan 3E FPGA board.
- **Simulation and Testing**: Testbenches provided to simulate the LED and switch control logic.

## Project Structure
- **`src/`**: Contains Verilog source files for LED and switch control logic.
- **`testbench/`**: Includes testbench files for simulation and testing.
- **`docs/`**: Documentation related to the project, including schematics and reference materials.
- **`constraints/`**: UCF (User Constraints File) for mapping FPGA pins to LEDs and switches.

## Prerequisites
- **Xilinx ISE Design Suite**: Required for synthesizing and simulating the Verilog code.
- **Spartan 3E FPGA Development Board**: The FPGA board used for this project.
- **LEDs and Switches**: Connected to the Spartan 3E FPGA board according to the constraints file.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MinhThien-2702/VERILOG-LED-AND-SWITCH-SPARTAN-3E-FPGA.git
   cd VERILOG-LED-AND-SWITCH-SPARTAN-3E-FPGA

2. **Open the project in Xilinx ISE**:

Open Xilinx ISE Design Suite.
Create a new project and add the Verilog source files from the src/ directory.
Set up the constraints using the UCF files in the constraints/ directory.
3. **Compile and Synthesize**:

Compile the Verilog code to ensure there are no syntax errors.
Synthesize the design to generate the bitstream file for programming the FPGA.
4. **Simulate the Design**:

Use the provided testbench files in the testbench/ directory to simulate the LCD control logic.
Verify that the simulation output matches the expected behavior.
5. **Program the FPGA**:

Connect the Spartan 3E board to your computer.
Use the generated bitstream file to program the FPGA.
Connect the LCD to the FPGA following the documentation provided.
6. **Run the Project**:

Once the FPGA is programmed, observe the output on the LCD display.
Modify the Verilog code as needed to customize the display functionality.

## Contributing
Contributions are welcome! If you have improvements or new features to add, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or feedback, please contact Nguyễn Minh Thiện at minhthien2047@gmail.com