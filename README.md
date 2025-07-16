# 🌿 The Green Algorithms: Measuring Sustainability in AI

> A capstone project analyzing the environmental impact of AI models and proposing a composite sustainability metric called the **Green Score Index**.

![Banner](images/green-algorithms-banner.png)

---

## 📘 Project Overview

As AI adoption grows rapidly, so does its **carbon footprint**. This project investigates how different AI models impact the environment in terms of **energy consumption, emissions, and water usage**. We propose a metric — the **Green Score Index (GSI)** — to benchmark AI systems based on **performance + sustainability** rather than performance alone.

---

## 🎯 Objectives

* Quantify **CO₂ emissions**, energy usage, and water consumption of various AI models.
* Develop a **Green Score Index (GSI)** to rank models based on sustainability.
* Compare AI model types (NLP, CV, Recommender, Speech) across **cloud regions and energy sources**.
* Recommend **eco-conscious AI deployment strategies**.

---

## 🧪 Methodology

### 🗃️ Datasets Used

* **Operational Dataset (10 columns)**: Model Type, Training Hours, Energy Consumption, Accuracy, etc.
* **Environmental Dataset (10 columns)**: Region, Energy Source, PUE, CO₂ Intensity, Water Usage, etc.

### 🛠️ Tools & Technologies

* **Python**: Data simulation, analysis, and visualizations (Pandas, NumPy, Seaborn, Matplotlib)
* **Jupyter Notebook**: Implementation and modeling
* **Excel**: Tabulation & summarization
* **VOSviewer**: Literature review analysis

### 📊 Visualizations

* Bar charts for emissions by model type and region
* Scatter plots showing accuracy vs emissions
* Heatmaps and boxplots for sustainability comparisons
* Composite Green Score Index ranking chart

---

## 🧠 Green Score Index (GSI)

The **Green Score Index** is a composite metric that blends:

* **Operational Efficiency** (energy per accuracy)
* **Environmental Load** (CO₂ per training hour)
* **Data Center Sustainability** (PUE, renewable %, water usage)

> 💡 A higher GSI = Better sustainability with competitive accuracy.

---

## 📈 Key Findings

* **Transformer & CV models** have the highest emissions; **Speech & Recommenders** are more efficient.
* **Canada-Central region** showed the lowest emissions; **US-East** and **EU-West** the highest.
* Google Cloud performed better than AWS and Azure due to higher renewable usage.
* Models with the same accuracy can emit **4x different emissions**, proving the need for green benchmarking.

---

## 💡 Recommendations

* Use **renewable-powered regions** (e.g., Canada-Central).
* Optimize models via **pruning, quantization, transfer learning**.
* Integrate **carbon tracking** in model evaluation.
* Encourage **Green AI competitions** and open scoring frameworks.

---

## 🌍 Future Scope

* Deploy real-time **emission dashboards** via cloud APIs.
* Expand dataset with real-world AI training data.
* Create open-source GSI plugins for TensorFlow/PyTorch workflows.
* Build institutional policies for **carbon-aware research**.

---

## 📌 Project Structure

```
green-algorithms/
│
├── notebooks/               # Jupyter notebooks with all code & analysis
├── datasets/                # Synthetic datasets: operational.csv, environment.csv
├── images/                  # Visualizations for README & presentation
├── final_report.pdf         # Capstone project document
└── README.md                # You're here!
```

---

## 📸 Sample Visuals

![Model Type Emissions](<img width="726" height="438" alt="Screenshot 2025-07-16 194731" src="https://github.com/user-attachments/assets/4d6c043a-8fdb-42b0-aadd-1e8c4aab6251" />)
*Emissions comparison by AI model type*

![Green Score Index](<img width="2400" height="1400" alt="green_score_index_by_model_type" src="https://github.com/user-attachments/assets/c0bd81b5-04a2-406e-bb63-8cb8c6e51201" />)
*Top 10 most sustainable AI models ranked by GSI*

---

## 👩‍💻 Team & Credits

* **Author:** Prakash Kumar
* **University:** Chandigarh University
* **Mentor:** Guide Name

---

## 📄 License

This project is licensed under the MIT License. You are free to use, modify, and distribute with attribution.

---

## 🙌 Acknowledgments

Grateful to our faculty, peers, and online AI communities whose insights shaped the direction of this project.

---

🌟 If you found this project useful or inspiring, please consider starring it!
