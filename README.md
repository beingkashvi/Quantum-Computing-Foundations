# Quantum Gates and Algorithms in Qiskit & PennyLane

This repository contains a hands-on implementation notebook exploring **quantum gates, circuit behavior, and foundational quantum algorithms** using both **Qiskit** and **PennyLane**.

The project is designed as a practical learning and comparison exercise between two popular quantum computing frameworks. It includes circuit construction, statevector analysis, entanglement experiments, measurement simulation, and implementations of core algorithms such as **Deutsch**, **Deutsch–Jozsa**, **Bernstein–Vazirani**, **Simon’s algorithm**, and **Grover’s algorithm**.

## Overview

The notebook demonstrates:

- Basic single-qubit and multi-qubit gate operations
- Statevector and unitary analysis
- Entangled vs separable circuits
- Circuit visualization and measurement statistics
- Side-by-side implementations in **Qiskit** and **PennyLane**
- Introductory quantum algorithms and oracle construction

This project was built to strengthen my understanding of quantum circuit design and the practical differences between software frameworks for quantum programming.

## Contents

The notebook is organized into the following sections:

### 1. Qiskit Fundamentals
- Single-qubit circuits with **X** and **H** gates
- Statevector inspection
- Probability extraction and sampled measurements
- Operator / unitary visualization
- Three-qubit Hadamard circuits

### 2. Entanglement and Measurement
- Bell-style entangled circuit construction
- Simulation with `BasicSimulator`
- Histogram-based result analysis
- Comparison between:
  - **Entangled circuits**
  - **Uncorrelated Hadamard circuits**

### 3. Quantum Gate Summary
A broader gate demonstration section including examples of:
- Pauli gates
- Hadamard
- Controlled operations
- Multi-qubit behavior
- Toffoli-style constructions

### 4. PennyLane Fundamentals
Equivalent implementations of the earlier concepts using PennyLane:
- QNodes and devices
- State return values
- Shot-based sampling
- Circuit drawing
- Entangled and separable circuit behavior

### 5. Quantum Algorithms
Implemented algorithms include:

- **Deutsch Algorithm**
- **Deutsch–Jozsa Algorithm**
- **Bernstein–Vazirani Algorithm**
- **Simon’s Algorithm**
- **Grover’s Algorithm**

The notebook includes oracle creation logic, circuit construction, and basic interpretation of measured outputs.

## Tech Stack

- **Python**
- **Qiskit**
- **PennyLane**
- **NumPy**
- **Matplotlib**
- **SciPy**

The notebook also contains commented code for connecting to **IBM Quantum Runtime**, which can be extended to run experiments on real quantum hardware.

## File Structure

```text
quantum_implementations.ipynb   # Main notebook containing all implementations
```

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate
```

On Windows:
```bash
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install qiskit pennylane matplotlib numpy scipy pylatexenc
```

### 4. Launch Jupyter
```bash
jupyter notebook
```

Then open:

```text
quantum_implementations.ipynb
```

## Key Learning Outcomes

Through this project, I explored:

- How quantum gates transform computational basis states
- The difference between **superposition**, **entanglement**, and **independent qubit behavior**
- How to interpret measurement counts from simulation
- How standard quantum algorithms use **oracles**, **interference**, and **measurement**
- Practical differences in implementing the same ideas in **Qiskit** vs **PennyLane**

## Notes

- This repository is primarily an **educational and exploratory implementation project**.
- Some algorithm sections are simplified to illustrate the underlying concepts clearly.
- Simon’s algorithm, in particular, is implemented as a demonstration of circuit structure rather than a full classical post-processing pipeline.
- IBM Quantum Runtime code is included in commented form and may require account setup before use on real hardware.

## Why this project matters

Quantum computing sits at the intersection of algorithms, physics, and software systems. By implementing the same concepts across two frameworks, this project reflects my interest in:

- quantum algorithms,
- scientific computing,
- framework-level understanding,
- and research-oriented experimentation.

## Future Improvements

Possible extensions include:

- running selected circuits on real IBM Quantum hardware,
- adding noise-model analysis,
- benchmarking Qiskit vs PennyLane workflows,
- extending Grover and Simon implementations,
- and reproducing results from published quantum computing papers.

