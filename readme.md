# Federated Learning Research Portal & Interactive Dashboard

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-TailwindCSS-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Status](https://img.shields.io/badge/Status-Active%20Research-success.svg)]()

A comprehensive, research-backed interactive web application and portal dedicated to **Federated Learning (FL)**. This platform synthesizes foundational literature, architectural workflows, optimization algorithms, security challenges, and real-world domain applications into a clean, modern single-page dashboard.

---

## 🌟 Key Features

1. **Interactive Architecture Visualizer & Simulator**
   - Step-by-step simulation of the core FL workflow across decentralized edge nodes (Hospitals, Mobile Fleets, Banking Nodes, IoT Devices) and a central aggregator.
   - Real-time epoch tracking, accuracy growth curves, loss reduction metrics, and live execution logs.
2. **Seminal Research Literature & Landmark Papers**
   - Direct breakdowns of foundational papers including McMahan et al. (Google, 2016/2017) on **FedAvg**, Li et al. (CMU, 2018) on **FedProx**, and Bonawitz et al. (CCS 2017) on **Secure Aggregation**.
3. **Algorithm Comparison Matrix**
   - Detailed breakdown of mathematical properties, convergence behaviors, and trade-offs for **FedSGD**, **FedAvg**, **FedProx**, and **FedDyn**.
4. **Security, Cryptography & Privacy Protections**
   - Deep dive into **Differential Privacy (DP)**, **Secure Aggregation (SecAgg)**, and **Byzantine Robustness** against model poisoning and membership inference attacks.
5. **Real-World Domain Applications**
   - Exploration of FL utility in **Healthcare & Genomics** (HIPAA/GDPR-compliant EHR training), **Banking & Fraud Detection**, and **Edge IoT**.

---

## 🚀 Quick Start / Running Locally

Because this project is built as a self-contained, single-file web application using Tailwind CSS via CDN, you don't need any complex Node.js build steps, Webpack, or backend servers to run it!

1. Clone or download this repository to your local machine:
   ```bash
   git clone https://github.com/diksha1829/Federated-Learning-FL-
   ```
2. Navigate into the project folder:
   ```bash
   cd Federated-Learning-FL-
   ```
3. Open `index.html` directly in any modern web browser:
   - **macOS:** `open index.html`
   - **Linux:** `xdg-open index.html`
   - **Windows:** Double-click `index.html` or open via your browser.

---

## 📐 Project Structure

```text
├── index.html       # Complete single-file web application (HTML + Tailwind CSS + JS)
└── README.md        # Documentation and GitHub repository guide
```

---

## 🔬 Featured Research Papers

- **FedAvg:** McMahan et al., *Communication-Efficient Learning of Deep Networks from Decentralized Data*, AISTATS 2017. ([arXiv:1602.05629](https://arxiv.org/abs/1602.05629))
- **FedProx:** Li et al., *Federated Optimization in Heterogeneous Networks*, MLSys 2020. ([arXiv:1812.06127](https://arxiv.org/abs/1812.06127))
- **SecAgg:** Bonawitz et al., *Practical Secure Aggregation for Privacy-Preserving Machine Learning*, CCS 2017. ([arXiv:1711.02587](https://arxiv.org/abs/1711.02587))

---

## 🤝 Contributing

Contributions, research additions, or algorithmic improvements are welcome! Please feel free to fork the repository, open an issue, or submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewAlgorithm`)
3. Commit your Changes (`git commit -m 'Add support for FedNova algorithm'`)
4. Push to the Branch (`git push origin feature/NewAlgorithm`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
