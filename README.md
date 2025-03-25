📘 Repository: AI-Based UX Risk Prediction for Smart Contracts in Web3
This repository contains the dataset, code, and analysis used in the research paper titled:

"AI-Driven UX Optimization for Sustainable Smart Contract Execution in Web3 Applications"

🔍 Project Overview
In decentralized applications (DApps), inefficient smart contracts are a major cause of energy usage, wasted gas fees, and poor user experience (UX).  In order to anticipate and address UX issues prior to deployment, this project suggests a machine learning-based method that has been trained on 10,000 Ethereum transactions.

 We determine the main factors that influence UX risk, including transaction type, complex function logic, and gas efficiency, using a Random Forest classifier with explainable AI (SHAP).  With a 99.75% accuracy rate, our model offers developers, UX researchers, and blockchain projects focused on sustainability useful insights.


📁 Contents
UX_Risk_Analysis.ipynb: Full Jupyter notebook including:

 Features Engineering 

 Training of models (Logistic Regression, Random Forest, and Gradient Boosting)

 Visualizations of SHAP explainability

 Impact analysis based on scenarios (cost, energy, and UX)

 eth_ux_dataset.csv: The study's cleaned Ethereum transaction dataset

 figures/: Every important figure used in the article, including gas waste charts, SHAP plots, and UX risk distributions

 README.md: Overview of the project and usage manual

 requirements.txt: Requirements for setting up the local environment


💡 Use Cases
Include UX risk prediction in CI/CD workflows for smart contracts.
 Cut down on the number of unsuccessful transactions and gas fee waste
 Lead UX audits for systems such as DeFi, NFT, and Web3.
 Boost blockchain networks' energy efficiency

♻️ Sustainability & Impact
In order to enable sustainable and user-friendly DApp ecosystems, our technology predicts a 90% decrease in gas fee waste, an 80% reduction in energy use, and a 70% drop in user drop-off rates.


