![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)
Hybrid Recommender System with Reinforcement Learning-Based Dynamic Pricing

📌 Project Overview

This project builds a hybrid recommender system that combines behavioral event data with item metadata to generate personalized recommendations and dynamically adjust pricing using reinforcement learning.

The system leverages user interaction history (views, add-to-cart, transactions) and product attributes to model user preferences, optimize recommendations, and simulate adaptive pricing strategies.

This project focuses on:

Large-scale event data preprocessing

Feature engineering from user–item interactions

Hybrid recommendation modeling

Reinforcement learning-based dynamic pricing logic

Model evaluation and performance comparison

📊 Dataset

The project uses e-commerce behavioral data including:

events.csv – user interaction events

item_properties_part1/2.csv – product metadata

category_tree.csv – product hierarchy

The dataset captures:

User session behavior

Item interactions

Product category structure

Time-based activity patterns

Due to file size constraints, raw datasets are not included in this repository.

🏗️ System Architecture

The project is structured as:

hybrid-recommender-rl-pricing/

├── data/

├── diagrams/

├── notebooks/

├── results/

├── README.md

├── requirements.txt

└── .gitignore

Key Components

Data preprocessing and cleaning

Feature extraction from user-item interactions

Hybrid recommendation logic

Reinforcement learning-based pricing strategy

Model training and validation

Performance visualization

The system integrates both collaborative behavior patterns and product-level signals to improve recommendation quality.

🤖 Modeling Approach

1️⃣ Hybrid Recommendation Strategy

Behavioral aggregation of user interactions

Item-level feature representation

User–item interaction modeling

Combined collaborative + content-based signals

2️⃣ Reinforcement Learning for Pricing

Simulated reward mechanism

Dynamic pricing policy adjustment

Iterative optimization of pricing decisions

Exploration vs exploitation balance

📈 Results

Model performance was evaluated using validation metrics and training curves.

Validation Loss Comparison Across Models

![Validation Loss](results/validation across all models.png)

Training vs Validation Loss (Best Model)

The final model demonstrates:

Stable convergence

Reduced validation loss

Improved generalization performance

💡 Business Impact

This framework can be applied in:

E-commerce personalization

Dynamic pricing engines

Demand-aware price optimization

User engagement maximization

By integrating recommendation and pricing strategies, businesses can optimize both conversion rates and revenue generation.

🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Reinforcement Learning concepts

Jupyter Notebook

🚀 How to Run

Install dependencies:

pip install -r requirements.txt

Open notebooks inside the notebooks/ directory.

Run preprocessing and model training cells sequentially.

📌 Future Improvements

Real-time deployment pipeline

Deep learning-based recommendation models

Advanced policy gradient methods for pricing

A/B testing simulation




