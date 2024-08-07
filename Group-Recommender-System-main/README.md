# Group Recommender System

## Overview

In this project, we implement a Group Recommender System based on matrix factorization techniques, using the Alternating Least Squares (ALS) algorithm. The system aims to provide recommendations for groups of users, considering their collective preferences.
![img-2](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/d37bc321-c2da-4065-88dc-dad38368906f)
![img-4](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/d4b7191a-c63b-441a-9c94-b2a0d5fa1833)

## Matrix Factorization for Recommendation

Matrix factorization is the core methodology used in collaborative filtering-based recommendation systems. It involves breaking down the user-item interaction matrix into user and item factor matrices, revealing latent features. Recommendations are then made based on these latent features.

![img-5](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/1fab3a56-3090-4f1a-94a9-c8b94376a1e6)

### Matrix Factorization using ALS Algorithm

We utilize the Alternating Least Squares (ALS) algorithm to factorize the user-item rating matrix. ALS iteratively learns latent factors for users and items by optimizing one factor matrix while fixing the other. The process continues until convergence.
![img-6](https://github.com/RishabhSrivastava-17/Group-Recommender-System/assets/72572136/23be3f77-faac-42af-8fa3-6ce4566da15e)

## Preference Aggregation

This project involves generating groups of users with user-defined sizes and predicting group ratings. We consider various techniques for preference aggregation:

- Majority-based strategies (e.g., Plurality Voting) that use the most popular items for aggregation.
- Consensus-based strategies (e.g., Average, Average without Misery, Fairness) that take into account the preferences of all group members.
- Borderline strategies (e.g., Dictatorship, Least Misery, Most Pleasure) that only consider a subset of preferences.

## Research Paper

The project is based on the research paper available at [this link](https://www.sciencedirect.com/science/article/pii/S0020025516300196).

## Dataset

We used the following dataset files for our project:

- [Movie_Id_Titles.csv](https://media.geeksforgeeks.org/wp-content/uploads/Movie_Id_Titles.csv)
- [file.tsv](https://media.geeksforgeeks.org/wp-content/uploads/file.tsv)

## References

- [NVIDIA Data Science Glossary - Recommendation System](https://www.nvidia.com/en-us/glossary/data-science/recommendation-system/)
