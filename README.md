# **Extensive review of Benchmarking Quantum Computers**
## **Joint Summer Internship, QKrishi & IISER Tirupati** 

**Supervisor:** Dr. Chetan Waghela, Doctoral Researcher in Quantum Optics in IIT Ropar

The project [report](https://github.com/SoumikSamanta10/Extensive-review-of-Benchmarking-Quantum-Computers/blob/dcec2b3b7b1144a7f63c370914472848f19faa8d/Extensive%20review%20of%20Benchmarking%20Quantum%20Computers.pdf) in the folder `Report'.

## **Project Description:**

•	Discussed various aspects of some of such benchmarking schemes to measure power and performance of Quantum Computer.

•	Analyzed Low-level benchmarks for charactering few-qubit devices, or a few qubits at a time in a large device like Quantum State Tomography, Randomized Benchmarking.

•	Recent methods that have better scalability like Quantum Volume, Cross Entropy Benchmarking.

•	Application-oriented benchmarks that test the performance of quantum computers on practically relevant tasks like Algorithms Based Benchmarking.

•	Simulated Randomized Benchmarking code using qiskit - 

We implemented randomized benchmarking on 2-qubit simultaneous with 1-qubit, establishing a Error per Clifford (EPC) 1.320763e-02. In this particular experiment, we have 3 qubits Q0,Q1,Q2. We are running 2Q RB (on qubits Q0,Q2) and 1Q RB (on qubit Q1) simultaneously, where there are twice as many 1Q Clifford gates. We define a noise model for the simulator. To simulate decay, we add depolarizing error probabilities to the CNOT and U gates.  We execute these sequences, but with a noise model extended with T1/T2 thermal relaxation error, and fit the exponentially decaying curve. We count the number of gates per Clifford, and calculate the two-qubit Clifford gate error, using the predicted primitive gate errors from the coherence limit.


## **Code Repo Descriptions:**
1) This repo consists [RB code](https://github.com/SoumikSamanta10/Extensive-review-of-Benchmarking-Quantum-Computers/blob/e9c73d4670a607cfbcf1873929a24a00ef45ddc4/RB%20code.ipynb) on simulation of randomized benchmarking.
2) These files cannot be run as it is. To run these files you need to create an account with IBM Quantum and empty workspace and copy-paste/upload the files onto the workspace. Running the files after that should do the job.



