# DistQC
Distributed Quantum Computing

NetQASM - installed

SquidQASM - needs UID+PWD from NetSquid

SimulaQron - installed, but old version of SquidQASM

All these tools are for simulating the network protocol.

## Aim

analysis communication resource vs. network structure

QPU-1: #qubits = A

QPU-2: #qubits = B

QPU-1 - QPU2 Network = C EPR pair / sec

1) how do we partition an algorithm that has Q <= A+B

2) how do we quantify/optimize that requirement of EPR pair.
    a) minimize number of EPR pair
    b) maintain maximum EPR pair/sec bound

3) can this problem be represented as PetriNet, StateMachine, ZX-Calculus... instead of QUBO
