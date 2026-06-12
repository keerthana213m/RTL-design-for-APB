FILE DESCRIPTION :

### 📄 APB Protocol Overview ("about_APB - pdf")

Contains the theoretical background of the Advanced Peripheral Bus (APB), including its architecture, signal descriptions, transaction phases, and timing diagrams. This document helps understand the protocol used in the RTL implementation.

### 💻 Design Code (`design_code_APB`)

Contains the Verilog RTL implementation of the APB-based SPI interface. The design includes APB control logic, SPI communication logic, state machines, and data transfer functionality between the APB bus and SPI peripheral.

### 🧪 Testbench Code (`testbench_code_APB`)

Contains the verification environment used to simulate and validate the design. The testbench generates clock and reset signals, applies APB read/write transactions, monitors SPI communication, and verifies correct functionality through simulation waveforms.

### 📊 Simulation Results (`__output__.pdf`)

Includes waveform outputs and simulation screenshots demonstrating successful APB transactions and SPI data transfers, verifying the correctness of the RTL design.

## Project Objective

Design and verify an APB-based SPI interface in Verilog RTL to enable communication between an APB master and SPI peripheral while ensuring protocol compliance and reliable data transfer.

