# Qubit Spin Dynamics Simulation with QuTiP

This project simulates the Larmor precession of a single qubit in a constant magnetic field along the z-axis. It uses QuTiP (Quantum Toolbox in Python) to solve the Schrödinger equation and visualizes the results in two ways:
1.  As 2D plots of the $\langle S_x \rangle$, $\langle S_y \rangle$, and $\langle S_z \rangle$ expectation values over time.
2.  As an animation on the Bloch sphere.

This project was built as part of my portfolio for the MSc in Quantum Technologies at UCL.

## Technologies Used
* **Python**
* **QuTiP** (Quantum Toolbox in Python)
* **NumPy**
* **Matplotlib**

## How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/VedantMahadik-qc/Spin-Dynamics-QuTiP.git](https://github.com/VedantMahadik-qc/Spin-Dynamics-QuTiP.git)
    ```
2.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3.  Open and run the `Simulating Spin Dynamics.ipynb` file in a Jupyter Notebook or Google Colab environment.

## Key Results

The simulation is initialized in the `|+x>` state and evolves under the Hamiltonian $H = -\omega \sigma_z$.

### 1. Expectation Values
This plot shows the time evolution of the $\langle S_x \rangle$, $\langle S_y \rangle$, and $\langle S_z \rangle$ operators. As expected, the state precesses around the z-axis, with $\langle S_x \rangle$ and $\langle S_y \rangle$ oscillating, while $\langle S_z \rangle$ remains constant at 0.

<img width="582" height="441" alt="image" src="https://github.com/user-attachments/assets/5fa56fb6-baa7-40ef-a861-da4868c78127" />


### 2. Bloch Sphere Animation
This animation shows the state vector precessing around the z-axis on the Bloch sphere.

<img width="519" height="519" alt="image" src="https://github.com/user-attachments/assets/22166028-70e1-41e7-9427-896af1571e26" />
