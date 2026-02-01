Name: Nandhu Rajesh N  
Roll Number: 2025EMAI10026 
Name of the Course: DSC524 Designing MlOps for Enterprises  
Course Offered in: Jan-June 2026  
Institute: Indian Institute of Information Technology Kottayam  
Date: 01 Feb 2026  

## Dataset: Palmer Penguins
Source: UCI Machine Learning Repository  
Species: Adelie, Gentoo, Chinstrap  

Summary:
- Number of samples: 344
- Number of features: 7
- Target variable: Species
- Missing values observed: Yes

## Manual Experiment Tracking Table

| Experiment ID | Model Type     | Hyperparameters     | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|---------------|---------------|---------------------|---------------------|------------------|------------------|-----------|-----------|
| EXP-01        | Decision Tree | Default             | None                | All features     | 80/20            | 0.78      | 0.80      |
| EXP-02        | Decision Tree | Max depth = 5       | Scaling             | Selected         | 80/20            | 0.82      | 0.85      |
