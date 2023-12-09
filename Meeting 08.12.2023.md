---
data: 08.12.2023
People: Jan, Marie, Jakob
---

## Main taking points
- Homodyne detection is a most popular method of measuring superconducting and spin qubits
- The idea is to imprint the state of the qubits on the state of the resonator, which is in the coherent state. This takes time $\tau$ 
- For the spin qubits, which suffer from low-frequency drift minimising $ \\tau $ is beneficial
- How much we can learn from low- $ \tau $ data

### How the data looks like
For the realistic data, I found how the blobs are being separated in time:

What I am changin is the integration time from 200ns (blue) to 4500 ns (black)
![Pasted image 20231209052756](Figures/Pasted%20image%2020231209052756.png)


![Pasted image 20231209052801](Figures/Pasted%20image%2020231209052801.png)

### Messy whiteboard

![Pasted image 20231209053151](Figures/Pasted%20image%2020231209053151.png)
### The ideas
- Play with hyphotesis testing and confidence intervals
- Employ Neural network to overpower naoive method
- Use Bayesian updates
- Compute reject probability?
- Try to use Q,I data to compute expectation values


### Mentioned papers
- Multiplexing and multi-qubit readout using deep learning in superconducting qubit https://arxiv.org/abs/2102.12481
- State of the art exeperiment in which they achive large blobs separation with short time (again superconducting qubits) https://arxiv.org/abs/2307.07765
- Machine learning distinction based on the trajectories http://arxiv.org/abs/2006.00109
