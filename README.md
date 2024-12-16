# NeuroSimLib
librería para simular redes neuronales biológicas basadas en el modelo Integrate-and-Fire (LIF)
# NeuroSimLib

## Biological Neural Network Simulation: Integrate-and-Fire (LIF) Model

**NeuroSimLib** is a Python library for simulating **biological neurons** using the **Leaky Integrate-and-Fire (LIF)** model. It allows modeling basic neural networks with synaptic connections, advanced plasticity rules like **STDP** (Spike-Timing-Dependent Plasticity), and dynamic visualization of neural activity.

---

## 🚀 **Features**

- **LIF Neuron Simulation**: Simulate single neurons using the classic Integrate-and-Fire model.
- **Neural Networks**: Create networks of multiple interconnected neurons.
- **Synaptic Connections**:
  - Fixed connections.
  - Synaptic plasticity rules, including **STDP** and **Hebbian Learning**.
- **Dynamic Visualization**:
  - Interactive real-time plots with **Plotly**.
  - Visualization of membrane potentials and spike times.

---

## 📥 **Installation**

Clone the repository and install the library locally using `pip`:

```bash
📊 Visualization
Dynamic and interactive visualizations can be generated using Plotly:

Membrane potentials over time.
Synaptic weight evolution during learning.

🔧 Dependencies
Python 3.8+
NumPy
Matplotlib
Plotly
Install dependencies using:

bash
Copiar código
pip install numpy matplotlib plotly

🧪 Examples
Explore the examples/ folder for detailed scripts:

single_neuron.py: Simulate a single LIF neuron.
multi_neuron_network.py: Simulate a network of interconnected neurons.
plasticity_demo.py: Demonstrates STDP plasticity.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributing
Contributions are welcome! If you'd like to add features, fix bugs, or improve documentation:

Fork the repository.
Create a new branch.
Submit a pull request.

🧠 About
NeuroSimLib was created to simulate basic biological neural networks and explore dynamic behaviors like spiking, plasticity, and learning.
