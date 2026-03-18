<div align="center">
  <img src="sources/Logo/bracu_logo_12-0-2022.webp" width="15%" height="auto" alt="BRACU Logo"/>
</div>

---

# Welcome to BRACU's Quantum Computing Notebook

<div align="center">

**An Interactive Learning Journey into the Quantum Realm**

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![Qiskit](https://img.shields.io/badge/Qiskit-2.3.1-purple.svg)](https://qiskit.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

</div>

---

## About This Course

This repository contains a **comprehensive collection of Jupyter notebooks & Markdown files** designed to guide you through the fascinating world of quantum computing. Whether you're a student, researcher, or enthusiast, these hands-on tutorials will help you understand quantum mechanics and develop practical quantum algorithms.

We utilize **Qiskit**, the powerful open-source quantum computing framework developed by IBM, as our primary toolbox for quantum exploration.

<p align="center">
<img src="sources/Logo/qiskit.gif" width="30%" height="auto" alt="Qiskit Framework"/>
</p>

---

## Quick Start

### Prerequisites
- **Python 3.11** (via pyenv)
- **Virtual Environment** support
- **pip** package manager

### Installation & Setup

```bash
# Create Python 3.11 virtual environment
"$(pyenv prefix 3.11.10)/bin/python" -m venv .venv
source .venv/bin/activate

# Install all required packages
pip install "qiskit[visualization]==2.3.1" qiskit_aer qiskit_ibm_runtime matplotlib pylatexenc prototype-zne

# Download helper modules
wget -O quantum_grader.py 'https://raw.githubusercontent.com/ahkatlio/BRAC-University-quantum-information/main/quantum_grader.py'
wget -O HiddenCode.py 'https://raw.githubusercontent.com/ahkatlio/BRAC-University-quantum-information/main/HiddenCode.py'

# Open the first notebook
jupyter notebook "Getting Set Up.ipynb"
```

For detailed setup instructions, see the **[Getting Set Up](Getting%20Set%20Up.ipynb)** notebook.

---

## What You'll Learn

Explore a comprehensive curriculum covering quantum computing fundamentals:
<p>In this notebook, you'll discover:</p>
  <ul>
      <li><strong>Forge your inaugural quantum circuit</strong> using Qiskit with hands-on examples</li>
      <li><strong>Execute quantum programs</strong> on real quantum computers via IBM Quantum</li>
      <li><strong>Master Qiskit fundamentals</strong> - the industry-standard quantum framework</li>
      <li><strong>Debug & troubleshoot</strong> quantum algorithms effectively</li>
      <li><strong>Understand quantum mechanics</strong> - from theory to practice</li>
      <li><strong>Key quantum concepts</strong>: Wave-Particle Duality, Quantization, Superposition, Entanglement, No-Cloning Theorem, Quantum Measurement</li>
      <li><strong>Classical vs Quantum Computing</strong> - what makes quantum special?</li>
      <li><strong>IBM Quantum Experience</strong> - account setup, lab, and composer tools</li>
      <li><strong>Quantum Bits (Qubits)</strong> - the building blocks of quantum computing</li>
      <li><strong>Quantum Gates</strong> - fundamental operations and their applications</li>
      <li><strong>Quantum Algorithms</strong> - Bell States, Bernstein-Vazirani, and more</li>
      <li><strong>Real-world applications</strong> of quantum computing in industry and research</li>
  </ul>


---

## Curriculum & Learning Path

### Let's Get Started
Your journey begins here with essential setup and verification:

| Module | Description | Duration |
|--------|-------------|----------|
| [Getting Set Up](Getting%20Set%20Up.ipynb) | Environment setup & Qiskit installation | 10 min |
| [Dirac Notation](materials/maths/Dirac%20Notation.md) | Mathematical foundation for quantum mechanics | 20 min |

### Quantum Fundamentals

| Module | Description | Duration |
|--------|-------------|----------|
| [Superposition](#scrollTo=6-AJIo88-Lsb) | Understanding quantum superposition | 25 min |
| [Qubits](#scrollTo=YcR6gLpS_MI8) | Quantum bits and their properties | 30 min |
| [Measurement](#scrollTo=_jHh1PkYQLue) | Quantum measurement and wave function collapse | 25 min |
| [Entanglement](#scrollTo=afLi79nxg2vr) | Quantum entanglement and correlations | 30 min |
| [Bloch Sphere](#scrollTo=SaxJgh_xxkAb) | Visualizing single-qubit states | 20 min |

---

## Technology Stack

| Tool | Purpose | Version |
|------|---------|---------|
| **Qiskit** | Quantum programming framework | 1.1.0 |
| **Qiskit Aer** | High-performance simulator | Latest |
| **Qiskit IBM Runtime** | Access to IBM quantum hardware | Latest |
| **Python** | Programming language | 3.11 |
| **Matplotlib** | Data visualization | Latest |
| **NumPy** | Numerical computing | Latest |
| **Jupyter** | Interactive notebooks | Latest |

---

## Project Structure

```
Quantum-Leap-101/
├── Getting Set Up.ipynb           # Setup & verification
├── README.md                       # This file
├── quantum_grader.py              # Homework grading utilities
├── HiddenCode.py                  # Workshop helper functions
├── requirements.txt               # Python dependencies
├── .venv/                         # Virtual environment
└── sources/
    ├── Logo/
    │   ├── bracu_logo_12-0-2022.webp
    │   └── qiskit.gif
    └── Author/
        └── AbdullahAlOmarGalib.jpeg
```

---

## Key Features

**Interactive Learning** - Run code cells directly in your browser  
**Comprehensive Curriculum** - From basics to advanced algorithms  
**Automatic Grading** - Built-in homework verification system  
**IBM Quantum Access** - Execute code on real quantum processors  
**Rich Visualizations** - Circuit diagrams and state visualizations  
**Hands-on Exercises** - Practice with real quantum programming  

---

## How to Use This Repository

1. **Clone the repository** to your local machine
2. **Install dependencies** using the Quick Start guide above
3. **Start with "Getting Set Up.ipynb"** to verify your environment
4. **Work through notebooks sequentially** following the curriculum
5. **Complete exercises** and use the grading system for feedback
6. **Experiment!** Modify code and explore quantum concepts

---

## Additional Resources

- **[Qiskit Official Documentation](https://qiskit.org/documentation/)** - Complete API reference
- **[IBM Quantum Experience](https://quantum-computing.ibm.com/)** - Access real quantum hardware
- **[Qiskit Textbook](https://qiskit.org/textbook/)** - Free interactive textbook
- **[Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/)** - Community Q&A

---

## Contributing

We welcome contributions! If you have suggestions, bug fixes, or new content:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## Author
<div align="center">

### Visionary & Creator

</div>

<table align="center" style="border: none; width: auto;">
  <tr>
    <td align="center" style="padding: 20px;">
      <img src="sources/Author/AbdullahAlOmarGalib.jpeg" width="100" height="120" style="border-radius: 50%; object-fit: cover;"/>
    </td>
    <td align="left" style="padding: 20px;">
      <h3>Abdullah Al Omar Galib (Ahkatlio)</h3>
      <p><strong>Founder & Lead Instructor</strong></p>
      <p><em>Mission:</em> Making quantum computing accessible to everyone</p>
      <p><strong>Motto:</strong> <em>"Brotherhood, respect, love, and we prosper."</em></p>
      <p>
        <a href="https://github.com/ahkatlio">GitHub</a> • 
        <a href="https://linkedin.com">LinkedIn</a>
      </p>
    </td>
  </tr>
</table>

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **IBM & Qiskit Community** - For the amazing quantum computing framework
- **BRACU (BRAC University)** - For institutional support
- **All Contributors** - For making this project better

---

## Support & Contact

- **Questions?** Open an issue on GitHub
- **Discussions** - Check out the GitHub Discussions tab
- **Found a bug?** Please report it [here](../../issues)

---

<div align="center">

### If you found this helpful, please give it a star!

Made for the quantum computing community

![GitHub stars](https://img.shields.io/github/stars/ahkatlio/Quantum-Leap-101?style=social)
![GitHub forks](https://img.shields.io/github/forks/ahkatlio/Quantum-Leap-101?style=social)

</div>

