# [Work in progress] Quantum chemistry applications: from classical to quantum
## ICCAD - What I learned during qccontest

This folder contains useful information I found during the qccontest regarding building and optimizing a vqe algorithm for the ICCAD QCContest (https://qccontest.github.io/QC-Contest/index.html). The problem was finding the ground state energy for the OH radical. Moreover, it contains additional information and implementation for the hartree fock algorithm.

The main points discussed in this repo are:
- Understanding the Hartree Fock algorithm, the hamiltonian represented in sto3g basis and implementing the (restricted) hartree fock algorithm classicaly
- The fermion to qubit mappings: especially the Jordan Wigner mapping (during the contest, we were restricted to using the aformentioned basis and mapping)
- How does the vqe work (for the NISQ era devices)
    - Choosing the right ansatz: finding balance between search space and available time
    - The estimator primitive (especially the noise mitigations) and the the algorithm behind vqe
- Noise Models, Noise mitigation techniques