# QPQE: Quantum Post-Quantum Encryption for Bitcoin

QPQE (Quantum Post-Quantum Encryption) is a quantum-secure Bitcoin wallet prototype developed for the Bitcoin 2025 Hackathon. Built by AI Quantum Cypher, QPQE uses IBM Qiskit for quantum random number generation and a proprietary Kyber-like post-quantum encryption to secure Bitcoin private keys against quantum threats. Features include a 16-qubit quantum circuit for randomness, Bitcoin address generation with ECDSA, and visualizations (text-based circuit, measurement distribution, key lengths comparison). Future plans include real Kyber integration, EEG-based authentication with NextMind, and Bitcoin testnet transactions. We’re seeking $250k-$1M for NIST standards testing and further development. Learn more at [quantumpqe.com](http://quantumpqe.com) or [www.aiquantumcypher.com](http://www.aiquantumcypher.com).

## Setup
1. Open in Google Colab: [Link to your notebook, if shared]
2. Install dependencies:
   ```bash
   !pip install qiskit qiskit-aer pycryptodome python-bitcoinlib cryptography matplotlib
