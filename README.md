# 🔍 Grover's Search Algorithm Visualizer

A Python implementation of **Grover's Search Algorithm** using **Qiskit** that demonstrates how quantum computing can search an unsorted database significantly faster than classical algorithms. This project builds and simulates Grover's Algorithm, visualizes the probability distribution of measurement outcomes, and illustrates the oracle and diffusion operations used in quantum search.

---

## 📌 Features

- Implements Grover's Search Algorithm from scratch
- Creates custom Oracle and Diffusion operators
- Simulates quantum circuits using Qiskit Aer
- Visualizes measurement results with histograms
- Displays matrix representations of quantum operators
- Supports different numbers of qubits and target states
- Educational implementation for learning Quantum Computing

---

## 🛠️ Technologies Used

- Python
- Qiskit
- NumPy
- Matplotlib

---

## 📂 Project Structure

```
Grover_Search_Algorithm_Visualizer.ipynb
README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Grovers-Search-Algorithm-Visualizer.git
```

### 2. Navigate to the project folder

```bash
cd Grovers-Search-Algorithm-Visualizer
```

### 3. Install the required packages

```bash
pip install qiskit qiskit-aer matplotlib numpy
```

---

## ▶️ Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
Grover_Search_Algorithm_Visualizer.ipynb
```

Run each cell sequentially to:

- Build the Oracle
- Apply the Diffusion Operator
- Execute Grover's Algorithm
- Simulate the circuit
- View measurement histograms
- Visualize quantum operator matrices

---

## 📊 Output

The project generates:

- Quantum circuit visualization
- Measurement histogram showing the searched state
- Oracle matrix visualization
- Diffusion operator matrix
- Grover operator visualization

---

## 📖 How Grover's Algorithm Works

1. Initialize all qubits into an equal superposition.
2. Mark the target state using an Oracle.
3. Amplify the probability of the target state using the Diffusion Operator.
4. Repeat the Grover iteration the optimal number of times.
5. Measure the qubits to obtain the desired search result with high probability.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Quantum superposition
- Quantum interference
- Oracle construction
- Amplitude amplification
- Quantum circuit simulation
- Fundamentals of Grover's Search Algorithm

---

## 🚀 Future Enhancements

- Interactive GUI using Streamlit
- User-defined target state selection
- Multiple marked states
- Animated circuit visualization
- Performance comparison with classical search
- IBM Quantum hardware execution

---
