

**“A Cirq-Enhanced Quantum Reinforcement Learning Model for High-Frequency Trading”**

---


# ⚛️ A Cirq-Enhanced Quantum Reinforcement Learning Model for High-Frequency Trading 📈

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Quantum](https://img.shields.io/badge/Quantum-Cirq-ff69b4)
![Status](https://img.shields.io/badge/Status-Research%20Prototype-yellow)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

> **🚀 A hybrid Quantum-Classical RL model built using [Cirq](https://quantumai.google/cirq) to optimize trading strategies in high-frequency financial markets.**

---

## 📜 Abstract

This research presents a novel **Quantum Reinforcement Learning (QRL)** framework using **Google's Cirq** to tackle challenges in **High-Frequency Trading (HFT)**. By merging quantum computing’s parallelism with RL's decision-making, the model optimizes stock trading strategies under volatile market conditions.

Key contributions:
- Cirq-based quantum circuit integration with trading agents
- Real-time stock data processing from **Alpha Vantage API**
- Enhanced Sharpe ratio and risk-adjusted returns
- OpenAI Gym-based trading environment with Buy/Hold/Sell logic

---


### 📊 Data Source

* **Stock:** AAPL (Apple Inc.)
* **Timeframe:** 24 years of historical daily data
* **API:** Alpha Vantage

---

## ⚙️ Technology Stack

| Component           | Tool/Library                              |
| ------------------- | ----------------------------------------- |
| Quantum Simulation  | [Cirq](https://quantumai.google/cirq)     |
| Trading Environment | [OpenAI Gym](https://www.gymlibrary.dev/) |
| ML Preprocessing    | Scikit-learn, NumPy                       |
| Data API            | Alpha Vantage                             |
| Visualization       | Matplotlib, Seaborn                       |
| Language            | Python 3.10                               |

---

## 🔁 Quantum Reinforcement Learning Process

### Quantum Circuit

* Uses **Hadamard (H)** gates to create superposition for state exploration
* **Measurement outcomes** determine the action: Buy / Hold / Sell
* Integration via `cirq.Simulator()` for iterative learning


circuit = cirq.Circuit()
circuit.append(cirq.H(q) for q in qubits)
result = cirq.Simulator().run(circuit)




## 📈 Results Summary

| Metric                | Observation                       |
| --------------------- | --------------------------------- |
| 📊 Cumulative Returns | +80% over training episodes       |
| 📉 Max Drawdown       | -15% to -30% (resilient recovery) |
| 📈 Sharpe Ratio       | 0.6 to 1.4 (improved risk-return) |
| 🔍 Exploration Policy | Epsilon decayed from 1 → 0        |

📌 **Visualizations** included in `/figures` folder:

* `cumulative_returns.png`
* `sharpe_ratio.png`
* `drawdown_curve.png`

---

## 🌟 Novelty

✅ Cirq-enhanced latency-tuned QRL model
✅ Live trading signals using streaming APIs
✅ First-of-its-kind hybrid model tuned for HFT with microsecond-level latency
✅ Supports **risk-aware trading** with reward calibration

---

## 📚 Future Work

* Integrate **quantum noise mitigation** for real-world testing
* Test across multiple assets (portfolio-level QRL)
* Real-time deployment using **quantum edge computing**
* Expand to **multi-agent systems** using quantum game theory

---

## 🧑‍💻 Authors

* **Dr. Santosh Kumar Yadav** – University of Delhi
* **Tavleen Kaur** – IGDTUW
* **Simer Khurmi** – IGDTUW
  ✉️ [simer.live@gmail.com](mailto:simer.live@gmail.com) | 📞 +91 9818933256

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* Google Quantum AI Team (Cirq)
* OpenAI Gym Developers
* Alpha Vantage for stock market data
* Quantum Finance Research Community

---

## 🔗 Related Resources

* [Cirq Documentation](https://quantumai.google/cirq)
* [Alpha Vantage API](https://www.alphavantage.co/)
* [Quantum Reinforcement Learning Overview](https://arxiv.org/abs/1803.00745)

---

## ⭐️ Star the Repo

If you find this project insightful, please ⭐ the repo and follow for future research updates in **Quantum Finance**.



