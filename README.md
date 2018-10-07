# Distinguishing-Unitary-Gates-on-IBM-Quantum-Processor
Qiskit 0.6 implementation of https://arxiv.org/abs/1807.00429<br> 
[![Build Status](https://travis-ci.org/euler16/Distinguishing-Unitary-Gates-on-IBM-Quantum-Processor.png?branch=master)](https://travis-ci.org/euler16/Distinguishing-Unitary-Gates-on-IBM-Quantum-Processor)

## Background
The paper is about distinguishing phase change gate and identity gate using a Quantum Circuit. The author discusses two schemes -
<ol>
<li>Parallel - using two qubits and applying the gate on both qubits </li>
<li>Sequential - using a single qubit </li>
</ol>

The circuit is then tested on IBM Quantum Processor.<br>
To run the Jupyter Notebook you will need to install Python 3.5+, qiskit 0.6 and an account on [[IBM Q](https://quantumexperience.ng.bluemix.net/qx)].

