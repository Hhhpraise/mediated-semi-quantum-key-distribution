# Mediated semi-quantum key distribution
This repository hosts the source code and documentation for a Mediated Semi-Quantum Key Distribution Protocol with Enhanced Control Operations Using Single Photons. The protocol is designed for secure key distribution leveraging quantum principles with mediated communication and specialized control operations. 

## Installation Instructions
To run the code, you need to have Qiskit installed. You can install Qiskit using pip:

`pip install qiskit`

## Usage Guide
You can run the code by executing the Python script. The code initializes a quantum circuit, performs quantum operations, simulates the circuit using Qiskit's Aer simulator, and visualizes the measurement outcomes using histograms.

### Explanation of Files and Directories
README.md: This file provides an overview of the repository and instructions for running the code.
MSQKD.ipynb: This Python script contains the implementation of the mediated semi-quantum key distribution protocol.

## Algorithm Overview
The protocol begins by initializing a quantum circuit with a specified number of qubits for Alice and Bob. Hadamard gates are applied to each qubit to initialize them in the plus state. Alice and Bob then perform random operations, either SIFT (quantum measurement) or CTRL (Discard and Replace with new qubit), on their respective qubits. Bell state measurements are performed between qubits from Alice and Bob, and the measurement outcomes are analyzed to establish a shared secret key.

## Notes and Considerations
The protocol assumes the absence of eavesdropping, but it includes checks to detect possible eavesdroppers.
The efficiency and security of the protocol depend on various factors, including the number of qubits, the randomness of operations, and the fidelity of quantum gates.
## Contributing Guidelines
Contributions to the repository are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact Information
For questions or inquiries about the code or protocol, please contact the repository owner.
