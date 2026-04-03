# BOAT: A Bi-level Optimization Auxiliary Toolbox

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub Issues](https://img.shields.io/github/issues/callous-youth/BOAT.svg)](https://github.com/callous-youth/BOAT/issues)
[![GitHub Stars](https://img.shields.io/github/stars/callous-youth/BOAT.svg)](https://github.com/callous-youth/BOAT/stargazers)

---

## 🌟 Why BOAT?
... (原有介绍内容) ...

---

## 🤝 Community & Contributing

We are building BOAT not just as a tool, but as a **community-driven** ecosystem for Bi-level Optimization research. We highly welcome contributions from the community!

* **Found a bug?** Open a [Bug Report](https://github.com/callous-youth/BOAT/issues/new?template=bug_report.md).
* **Have an idea?** Suggest a [Feature Request](https://github.com/callous-youth/BOAT/issues/new?template=feature_request.md).
* **Want to contribute code?** Please read our [Contributing Guide](./CONTRIBUTING.md).

### 🚀 Good First Issues
For newcomers, we have curated a list of [Good First Issues](https://github.com/callous-youth/BOAT/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) that are perfect for getting started with the codebase.

---

## 👥 Contributors

A huge thank you to all the people who have contributed to BOAT! 

<a href="https://github.com/callous-youth/BOAT/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=callous-youth/BOAT" />
</a>

*(Made with [contrib.rocks](https://contrib.rocks))*

---


# Contributing to BOAT

Thank you for your interest in contributing to **BOAT**! As an open-source research toolbox, we rely on community feedback and contributions to stay at the cutting edge of Bi-level Optimization (BLO).

By participating in this project, you agree to abide by our standards and maintain the quality of research code.

---

## How Can I Help?

### 1. Reporting Bugs 🐛
If you find a bug (e.g., incorrect gradients, crashes, or documentation errors), please open an Issue using the **Bug Report** template. Be sure to include:
* A minimal reproducible example.
* Your environment details (PyTorch version, OS, etc.).

### 2. Feature Requests 💡
Have an idea for a new BLO algorithm or a utility function? Open an Issue using the **Feature Request** template. We especially value implementations of algorithms from recent top-tier conferences (ICML, NeurIPS, CVPR, etc.).

### 3. Submitting Pull Requests (PRs) 🚀
1. **Fork** the repo and create your branch from `main`.
2. If you've added code that should be tested, **add tests**.
3. Ensure the code follows Python type-hinting and Google-style docstrings.
4. Issue a **Pull Request** describing your changes.

---

## Development Standards

To keep the library "research-ready" and "production-stable," we follow these rules:

* **Modularity:** New algorithms should inherit from our base classes to ensure compatibility with BOAT's engine.
* **Documentation:** Every new function must have clear docstrings explaining the mathematical parameters (e.g., inner/outer variables).
* **Correctness:** For gradient-related contributions, please provide a comparison with analytical solutions or established baselines if possible.

---

## Recognition & Authorship

We value every contribution:
* **Contributors Wall:** Your GitHub profile will be featured on our README.
* **Acknowledgments:** Significant contributors will be explicitly thanked in our documentation and future technical reports.
* **Collaboration:** For substantial algorithmic contributions, we are open to discussing deeper academic collaboration or co-authorship on related research papers.

---

## Questions?
If you have questions about the theory or implementation, feel free to start a [Discussion](https://github.com/callous-youth/BOAT/discussions) or contact the maintainer at `liuzhu@mail.dlut.edu.cn`.

## 📄 License
BOAT is released under the MIT License.


