# NMR_Quantum_Simulation

This repository contains a set of small NMR simulation projects based on purification and Trotterized time evolution. The work originated from the HQS Quantum Simulations Use Case Competition (2025), where our team received 2nd place, and was later extended with additional simulations and hardware runs on the IQM Emerald quantum processor.

The aim is to illustrate how a mixed NMR initial state can be embedded into a purified state, evolved under a two-spin Hamiltonian, and analyzed through both classical and quantum computational techniques.

---

## Overview

This project is organized into three main components:

- **Classical simulation:**  
  A reference computation of purified two-spin NMR dynamics using Trotterized time evolution.

- **IQM hardware runs:**  
  Two notebooks executed on the *IQM Emerald* quantum computer, including a two-spin case and an extended purification structure for a multi-spin (5-spin) model.

- **Main summary notebook:**  
  A cleaned and annotated notebook that consolidates the results and provides a clear explanation of the methods used.

This structure allows direct comparison between classical simulations, hardware executions, and the numerical tests performed during the HQS use case.

---

## Methods

- **Purification:**  
  The mixed initial state is represented as a pure state in an enlarged Hilbert space by coupling the system to an ancilla.

- **Trotterized time evolution:**  
  The NMR Hamiltonian is decomposed into easily exponentiable terms, and the evolution operator is approximated by a first-order Trotter product.

- **Observable extraction:**  
  Expectation values, density matrices, and NMR-like spectra are computed from the time-evolved state.

- **Hardware execution:**  
  Selected circuits were run on the IQM Emerald quantum processor and compared with classical predictions.

---
## Requirements

Hardware notebooks require access to the IQM client API (or a mock backend), but they can also be viewed offline without execution.

---

## Notes

- The aim of this repository is to demonstrate purification + Trotter evolution for small NMR models.  
- Classical and quantum results are intended to illustrate qualitative behavior, not optimized for performance.  
- This repository is part of my application to the HQS NMR use case in-house competition (2025).  

---

## Contact

**Ege Eroğlu**  
Karlsruhe Institute of Technology  
egeeroglu@gmail.com

