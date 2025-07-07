Postgraduate Project Research – Mutual Information Estimation
This repository contains the research work and preliminary implementation developed as part of my Postgraduate Project Assignment (PPA). The project investigates jackknife resampling as a method to improve the estimation of Mutual Information (MI), a key concept in information theory for measuring the relationship between two random variables.

Project Summary
Conventional MI estimators often suffer from bias and variance, especially when dealing with small or noisy datasets. This project explores the use of the jackknife resampling technique to reduce these issues. The aim is to:
- Review and analyze existing literature on MI estimation and bias reduction techniques
- Develop and implement algorithms for jackknife-based MI estimation
- Evaluate performance using synthetic datasets with varying sample sizes, noise levels, and dependency structures
- Compare jackknife MI estimates against standard estimation methods
- The expected outcome is to determine whether jackknife resampling provides more precise and reliable MI estimates, particularly for small datasets, contributing to both theoretical research and practical applications.

Repository Contents
- Jackknife_MI_Research.pdf — The final written report detailing the research background, methodology, and preliminary findings
- Jackknife_Approach.ipynb — A Jupyter notebook containing initial coding work for MI estimation using jackknife resampling on synthetic datasets

Technologies Used
- Python — primary language for implementation and experiments
- NumPy / SciPy / scikit-learn — for numerical computations and synthetic data generation
- Jupyter Notebook — for interactive experimentation and analysis
