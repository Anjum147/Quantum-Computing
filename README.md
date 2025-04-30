# Quantum-Computing

Linear Combination of Unitaries (LCU) Pauli Decomposition for Quantum Simulation
Overview
This repository implements a framework for simulating quantum evolution using Linear Combination of Unitaries (LCU) with Pauli decomposition. The method enables the implementation of non-unitary operations on quantum systems by combining unitary Pauli operations with an ancilla-assisted protocol.

Key Features
Pauli Decomposition: Decomposes arbitrary operators into linear combinations of Pauli strings

Ancilla-Assisted Evolution: Implements non-unitary operations using a single ancilla qubit

Flexible Simulation: Works with any number of qubits and various initial states

Visualization: Includes built-in plotting of quantum state evolution

Theory
The LCU method expresses a target operator A as:

A = Σᵢ cᵢ Pᵢ

where Pᵢ are Pauli operators and cᵢ are complex coefficients. 
