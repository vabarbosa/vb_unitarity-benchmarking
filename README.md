# unitarity-benchmarking
Implementation of Unitarity Randomized Benchmarking (URB) using IBM Qiskit.
For more information on theoretical aspects of URB, please refer to the following papers:
- Estimating the coherence of noise New J.Phys.17 (2015) 113020 
- Efficient unitarity randomized benchmarking of few-qubit Clifford gates Phys.Rev.A 99, 012315 (2019)

## Current Functionality
- Calculate unitarity of Clifford group gateset, for single and two-qubit gates.
- Supports benchmarking of custom noise models, including the noise simulation of real backend devices of IBM-Q.
- User controlled settings for noise due to state preparation, gate operation, per clifford gate operation and measurement.
- Supports calculation of unitarity for individual gate noise. 

## Installation
- Clone the repository and install the required packages. User must have IBM account for running the code on IBM-Q devices. Please visit www.qiskit.org for further details and installation of Qiskit. 
- This implementation also uses the QuaEC: Quantum Error Correction Analysis with Python a library for quantum error correction. Please visit https://www.cgranade.com/python-quaec/ for further details. However, for general unitarity experiments requiring no gatesets, this library may be omitted, with some modification in code.
