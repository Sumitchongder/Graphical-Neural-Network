# Contributing to the Hybrid GNN + LLM Framework

Thank you for your interest in contributing to this project 🧠  
Contributions from researchers, students, and practitioners in **graph learning, large language models, reinforcement learning, and AI systems engineering** are welcome.

---

## 🧪 Types of Contributions

We welcome contributions such as:

- New GNN architectures (GCN, GAT, Graph Transformers)
- Improvements to graph-to-text conversion pipelines
- LLM fine-tuning strategies (LoRA, QLoRA, DPO, PPO)
- Reinforcement learning–based evaluation metrics
- Agentic orchestration logic
- Hyperparameter optimization improvements
- Performance, scalability, or memory optimizations
- Documentation and reproducibility enhancements

---

## 🛠 Development Setup

### Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
````

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📐 Coding Standards

Please adhere to the following standards:

* Follow **PEP 8** for Python style
* Write clean, modular, and readable code
* Add docstrings to all public functions and classes
* Avoid hard-coded constants; use configuration files or parameters
* Use deterministic random seeds where applicable
* Ensure new code does not break existing pipelines or experiments

---

## 🧪 Research & Experimental Contributions

If contributing experiments or benchmarks:

* Clearly document:

  * Dataset or graph generation method
  * Model architecture and hyperparameters
  * Training and evaluation protocols
* Ensure experiments are reproducible
* Log artifacts (configs, metrics, plots) when appropriate
* Provide a concise interpretation of results

---

## 🔄 Pull Request Process

1. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Commit with clear, descriptive messages:

   ```bash
   git commit -m "Add GraphSAGE baseline with Optuna tuning"
   ```

3. Push to your fork and open a Pull Request

4. Include in your PR:

   * Summary of changes
   * Motivation and impact
   * Assumptions or limitations
   * Relevant references (if applicable)

---

## 📜 Licensing

By contributing, you agree that your contributions will be licensed under the **same license as this project**.

---

## 🙏 Acknowledgement

All contributors will be acknowledged.
Significant research or engineering contributions may be cited in future reports, demos, or publications.

Thank you for helping advance hybrid graph-centric AI 🚀
