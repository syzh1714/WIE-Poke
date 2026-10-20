# ⚡ Pokémon Legendary Classifier & Tactical Matchup Engine

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/your_notebook_name.ipynb)

A complete end-to-end machine learning project built in Google Colab that uses core combat telemetry to classify legendary Pokémon, analyze power distributions, and power an interactive head-to-head tactical matchup engine.

---

## 📌 Project Overview
This project explores multi-dimensional base stats from the classic Pokémon Kaggle dataset. It implements supervised learning classification models to distinguish standard Pokémon from elite anomalies (Legendaries) and includes a custom matching function to evaluate tactical matchups based on speed, defense, and combat score.

---

## 📂 Dataset Link
* **Source:** [The Complete Pokémon Dataset on Kaggle](https://www.kaggle.com/datasets/rounakbanik/pokemon)
* **Raw CSV Mirror Used in Code:** `https://raw.githubusercontent.com/armgilles/pokemon/master/pokemon.csv`

---

## 🚀 Setup Instructions
To run this project interactively:
1. Click the "Open in Colab" badge above or upload the `.ipynb` notebook into [Google Colab](https://colab.research.google.com/).
2. Run the code cells sequentially from top to bottom:
   * **Cell 1:** Import all required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`).
   * **Cell 2:** Load the dataset and calculate total base power and combat scores.
   * **Cell 3:** Run power comparison summaries and boxplot visualizations.
   * **Cell 4 & 5:** Prepare data (80/20 split, `StandardScaler`), train the **Decision Tree** and **K-Nearest Neighbors (KNN)** models, and view side-by-side confusion matrices.
   * **Cell 6:** Test the interactive **Head-to-Head Matchup Predictor** by entering any Pokémon name when prompted.

---

## 📊 Results & Evaluation
1. Models Tested: Decision Tree Classifier & K-Nearest Neighbors (KNN).
2. Performance: Both models achieved high predictive accuracy (>90%) due to the strong statistical correlation between base stats and legendary tier placement.
3.Visualizations: Includes Seaborn boxplots illustrating the power gap between normal and legendary groups, alongside side-by-side confusion matrix heatmaps evaluating model accuracy.

---

## 🏁 Conclusion
Key Findings: Decision Tree and KNN classifiers effectively isolate rare, elite tiers using quantitative telemetry. 
Takeaways: Demonstrates the vital role of feature scaling for distance-based algorithms like KNN and bridges statistical classification with practical, interactive tooling (tactical matchmaking).
