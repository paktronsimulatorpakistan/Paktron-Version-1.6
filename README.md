# Paktron-Version-1.6
PKTron (version 0.1.6) - Pakistan's 1st 100 Qubit Quantum Simulator

#PKTron: Pakistan Quantum Tron Simulator
PKTron Pakistan's 1st Quantum Simulator with 100 Qubits Capability Version 0.1.6 it has a library for quantum computing simulations, offering quantum circuit construction, quantum algorithms, and advanced visualizations integrated with machine learning capabilities. Released in October 2025

#Features
Quantum circuit simulation with statevector, stabilizer, and MPS backends
Implementation of quantum algorithms: QFT, Phase Estimation, Shor's, VQE, QAOA, HHL
Visualization tools: Histograms, Bloch spheres, density matrices
Machine learning integration with variational circuits and loss landscapes
Support for noisy simulations and error analysis
Installation

#pip install pktron

📦 Paktron 1.6v — Quantum Computing & Visualization Framework

pktron is a modular, beginner-friendly yet powerful quantum computing framework designed for simulation, algorithm prototyping, and rich visualization. It integrates quantum circuit construction, classical-quantum hybrid algorithms, and advanced plotting tools into a unified Python package.

Built with extensibility in mind, pktron bridges the gap between educational tools and research-grade experimentation.

🚀 Features
🧠 Quantum Circuit Simulation
Custom QuantumCircuit class for building and simulating quantum systems
Supports multiple backend types:
Statevector simulation
Stabilizer-style approximations (via backend extensions)
Flexible gate application system with internal state tracking
⚛️ Built-in Quantum Gates

Includes a comprehensive gate library:

Single-qubit gates: H, X, Y, Z, S, T, rotations (RX, RY, RZ)
Multi-qubit gates: CNOT, CZ, CY, SWAP, Toffoli
Gate history tracking for debugging and visualization
🧩 Quantum Algorithms

Pre-implemented algorithms for learning and experimentation:

Core Algorithms
Quantum Fourier Transform (QFT)
Phase Estimation
Grover’s Search
Shor’s Period Finding
Quantum ML / Hybrid
Variational Quantum Eigensolver (VQE)
Quantum Approximate Optimization Algorithm (QAOA)
Hybrid circuits via PennyLane integration
Educational / Custom
Quantum Flip
Quantum Treasure Hunt
Quantum Magic Spin
BB84 Quantum Key Distribution
📊 Advanced Visualization

Rich visualization tools powered by multiple libraries:

Histogram plots of measurement results
Bloch sphere visualization (via QuTiP)
Heatmaps and state distributions (Seaborn / Matplotlib)
Interactive plots using Plotly
Animated quantum state evolution (via ImageIO)
🤖 Quantum Machine Learning Tools
Variational circuits using PennyLane
Parameterized quantum models
Visualization of training landscapes and circuit behavior
⚙️ Backend System
Pluggable backend architecture
Built-in:
StatevectorSimulator
Tensor-based simulation via quimb
Extensible for custom simulators or hardware integration

📦 Installation
pip install pktron

Or from source:

git clone https://github.com/your-repo/pktron.git
cd pktron
pip install .
🔧 Dependencies
numpy
pennylane
matplotlib
quimb
networkx
plotly
seaborn
qutip
streamlit (optional for apps)
🧪 Example Usage
from pktron import QuantumCircuit, h, cnot

# Create a 2-qubit circuit
qc = QuantumCircuit(2)

# Apply gates
h(qc, 0)
cnot(qc, 0, 1)

# Execute
result = qc.run()

# Visualize
qc.plot_histogram()
🎯 Use Cases
📚 Quantum computing education
🔬 Algorithm prototyping
🤖 Quantum machine learning experiments
📊 Visualization of quantum states
🧪 Research simulations
🌟 Design Philosophy
Simplicity first — easy for beginners
Modularity — extend every component
Visualization-driven learning
Hybrid-ready — integrates classical + quantum workflows
🔮 Future Roadmap
Real quantum hardware support (IBM Q / AWS Braket)
Noise modeling and error correction
GPU acceleration
Web-based dashboards (Streamlit integration)
Circuit optimization tools
🤝 Contributing

Contributions are welcome! Feel free to:

Submit issues
Propose new algorithms
Improve visualizations
Extend backend support
📜 License

MIT License
