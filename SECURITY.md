# Security Policy

## 🔐 Responsible Disclosure

This project includes **machine learning pipelines, graph processing, LLM fine-tuning, and agentic workflows**.  
If you identify a vulnerability, correctness issue, or unsafe assumption, please do **not** open a public issue immediately.

Instead, report it responsibly to the project maintainer via private communication.

Please include:

- Description of the issue
- Affected components (GNN, LLM, RL, orchestration, data handling)
- Steps to reproduce (if applicable)
- Potential impact on correctness, safety, or reproducibility
- Suggested mitigation (optional)

---

## 🛡 Scope of Security Considerations

Relevant issues may include:

- Data leakage or unsafe serialization
- Incorrect assumptions in graph-to-text conversion
- Vulnerabilities in model fine-tuning workflows
- Reproducibility failures due to randomness
- Unsafe dependency usage or version conflicts
- Misleading evaluation or metric computation

---

## 📦 Supported Versions

Only the **latest version of the repository** is actively maintained.  
Users are encouraged to keep dependencies (PyTorch, Transformers, Optuna, CUDA drivers) up to date.

---

## ⚠️ Research Disclaimer

This repository is intended for **research, experimentation, and demonstration purposes**.

It is **not a production-ready AI system**, and outputs should not be used for safety-critical or regulated decision-making without additional validation.

---

## 🧾 Acknowledgement

We appreciate responsible disclosure and collaboration to maintain correctness, trust, and scientific rigor.

Thank you for helping keep this project secure and reliable 🔒
