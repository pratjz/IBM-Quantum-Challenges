<!--![image of qcchallenge logo](qcc_banner.png) -->

## Challenge Index
| Week  | Challenge | Message from Dr. Ryoko |
| ---     | ---    | --- |
| Week 0 |[For Beginners: The atoms of computation](exercises/week-0/ex_0_en.ipynb) | [Episode 1](https://youtu.be/eLw7fWb2xv4) |
| Week 1 |[Learning Challenge Exercise I-A](https://github.com/qiskit-community/IBMQuantumChallenge2020/blob/iqx/exercises/week-1/ex_1a_en.ipynb) <br/>[Learning Challenge Exercise I-B](https://github.com/qiskit-community/IBMQuantumChallenge2020/blob/iqx/exercises/week-1/ex_1b_en.ipynb)|  [Episode 2](https://youtu.be/f8TEd_51rHI) |
| Week 2  |[Learning Challenge Exercise II-A](https://github.com/qiskit-community/IBMQuantumChallenge2020/blob/main/exercises/week-2/ex_2a_en.ipynb) <br/>[Learning Challenge Exercise II-B](https://github.com/qiskit-community/IBMQuantumChallenge2020/blob/main/exercises/week-2/ex_2b_en.ipynb)| [Episode 3](https://youtu.be/kLizHnvTguE), [Episode 4](https://youtu.be/25PcR5Pn4hk) |
| Week 3  |[Final Challenge](https://github.com/qiskit-community/IBMQuantumChallenge2020/blob/main/exercises/week-3/final_en.ipynb) | [Episode 5](https://youtu.be/Bkk5-j6rpoM), [Episode 6](https://youtu.be/EC2Dc1QgLZY) |
 <br/>


## Final Exercise Submission Rules
For valid submissions we ask that your solution adheres to the below rule.<br/>
* Please implement the quantum circuit within **28 qubits**.
* Use Grover's algorithm you learned in Week1 & 2 with **iteration ＝ 1**.
* The initial state for Grover's algorithm must be equal probability distributions. For example, if you want use only 3 computational bases for 2 qubits instead of 4 as the initial state. Then, the state will be sqrt(1/3)(|00⟩+|01⟩+|11⟩).
* Please note that you can get the answer with the same endian as the one used in Week2 explanation. You should map the index of the problem into four classical registers c[0:4] in binary. c[0] is the highest bit and c[3] is the lowest bit. For example, when mapping 12, the furthest left bit of 1100 will be mapped to c[0].
* Make sure you **create an oracle** that **doesn't require knowledge of what the answers are**. (For example, you are not allowed to create an oracle by using a classical optimization solver to get your answers for it.)  
With the exception of the Unroller, which is required for decomposing your circuit to calculate quantum costs, you are not allowed to use any existing transpiler passes nor original transpilers for making simplifications in this competition.
* Please **do not run jobs in succession** even if you are concerned that your job is not running properly. This can create a long queue and clog the backend. You can check whether your job is running properly at: https://quantum-computing.ibm.com/results  
* Your score for this exercise will be same as the cost of your QuantumCircuit. The lower the cost, the better.
* Judges will check top 10 solutions manually to see if the solutions adhere to the rules. **Please note that your ranking is subject to change after the challenge period as a result of the judging process**. 
* Top 10 participants will be recognized and asked to submit a write up on how they solved the exercise.
* **When mapping the board information into your quantum circuit, you must not change the board information from the original one. (i.e. Do not rearrange the asteroid positions, nor rotate, invert, swap rows and columns.)** 
<br/>
