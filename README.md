# Qubit-owner-database-system

---

# Qubits Database with Quantum Circuit Simulation

## Overview

This project creates a SQLite database to store information about qubits along with their simulation using Qiskit, a quantum computing framework. Qubits are the fundamental building blocks of quantum computers, and this code helps manage qubit data while simulating their behavior.

## Features

- Creates an SQLite database named `qubits_database.db`.
- Defines a `Qubits` table to store qubit information.
- Defines a simple noise model with depolarizing errors for qubit simulations.
- Generates and transpiles a simple quantum circuit using Qiskit.
- Simulates the quantum circuit on a qasm simulator with noise.
- Retrieves actual measurements of gate fidelity and coherence time.
- Records qubit information including name, type, energy level, coherence time, gate fidelity, owner name, and run date in the database.
- Queries the database to retrieve qubit information.
- Provides a complete log of qubit information and simulation results.

## Elevator Pitch

Looking to manage and simulate qubits in your quantum computing projects? This code offers a comprehensive solution. It creates a SQLite database to store qubit details, simulates their behavior using Qiskit, and even accounts for noise in quantum circuits. With the ability to record important qubit parameters and access real measurements, you'll have a powerful tool at your disposal. Whether you're a quantum researcher, developer, or enthusiast, this project simplifies qubit management and enhances your quantum computing endeavors.

## Getting Started

1. Install the required packages using `pip install qiskit`.
2. Copy and paste the provided code into your Python environment.
3. Run the script to create the `qubits_database.db` database and perform qubit simulations.

## Customization

- Modify the quantum circuit to suit your needs.
- Adjust the noise model's error probability as required.
- Add or remove qubit information columns as necessary.

## Future Enhancements

- Incorporate more advanced noise models.
- Implement graphical visualization of qubit data and simulation results.

## Contributors

- [Stephen vega ]
- [Chat gpt]

## License

This project is licensed under the [MIT License](LICENSE).

--
