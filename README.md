# Qubit Dynamics Simulation with QuTiP

This project simulates fundamental qubit dynamics using QuTiP (Quantum Toolbox in Python). It was built as part of my portfolio for the MSc in Quantum Technologies at UCL.

The notebook is split into three parts:

1.  **Larmor Precession (Ideal):** Solves the Schrödinger equation (`sesolve`) for a qubit in the `|+x>` state evolving under an $H_z$ Hamiltonian. This shows the ideal, coherent precession of the state vector.

2.  **Rabi Oscillations (Ideal):** Solves the Schrödinger equation (`sesolve`) for a qubit in the `|+z>` state evolving under an $H_x$ Hamiltonian. This demonstrates coherent state-flipping, the basis of quantum gates.

3.  **Larmor Precession (Noisy):** Solves the Master equation (`mesolve`) for the same setup as Part 1, but adds a dephasing noise channel (`c_ops`). This simulates a more realistic, noisy qubit and shows the decay of coherence.

## Technologies Used
* Python
* QuTiP (Quantum Toolbox in Python)
* NumPy
* Matplotlib

## How to Run
1.  Clone the repository.
2.  Install the required libraries: `pip install -r requirements.txt`
3.  Open and run the `Simulating Spin Dynamics.ipynb` file in a Jupyter Notebook.

## Key Results
The notebook generates 2D plots and Bloch sphere animations for all three simulations, clearly showing the difference between ideal coherent evolution and noisy decoherence.
