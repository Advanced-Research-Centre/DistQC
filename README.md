# DistQC
Distributed Quantum Computing

## Software tools

### From TU Delft Quantum Internet team
1) NetQASM - installed
2) SquidQASM - needs UID+PWD from NetSquid. didn't work
3) SimulaQron - installed, but old version of SquidQASM

### Standard QSDK
All these tools are for simulating the network protocol. We can also use Qiskit, Q#, CirQ, tKet, braKet, cuQuantum.

## Aim

Mathematical modeling for the description of distributed quantum computation

Modeling tools or representations: Petri Net, Linear Logic, State Machines, ZX-Calculus, SAT, QUBO

### Simple case

QPU-1: #qubits = A

QPU-2: #qubits = B

QPU-1 - QPU2 Network = C EPR pairs/sec

1) How do we partition an algorithm that has Q <= A+B

2) How do we quantify/optimize the requirement of EPR pairs
    a) minimize the number of EPR pair
    b) maintain maximum EPR pair/sec bound

3) An example algorithm is Entanglement Swapping, using 2+2 qubits

## Related papers

### Circuit cutting
1) [2023 - Mapping quantum circuits to modular architectures with QUBO](https://arxiv.org/pdf/2305.06687.pdf)
2) [2021 - CutQC - Using Small Quantum Computers for Large Quantum Circuit Evaluations]

### Petri nets
1) [2021 - How to Bake Quantum into Your Pet Petri Nets and Have Your Net Theory Too]
2) [On a new model for Quantum Computers by using Quantum Petri Nets]
3) [Petri Nets, Discrete Physics, and Distributed Quantum Computation]
4) [Formal verification of quantum communication protocols using Petri nets]
5) [Modeling Grover's Algorithm with Colored Petri Net]
6) [Modeling of Quantum Computer by using Quantum Petri Net]
7) [2021 - Quantum Petri Nets](https://ieeexplore.ieee.org/abstract/document/9607302)
