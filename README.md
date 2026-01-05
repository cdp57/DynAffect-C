# Bridging Internal and External Forces in Emotion Dynamics

## Contributors
Charles Prince, Heath A. Demaree, Kyle J. LaFollette

## About
Affective experience reflects both internal momentum and external reactivity to situations, yet
most models capture only one. This limits our ability to explain whether affect will change or
remain stable. By applying a machine learning-based equation discovery algorithm to large-scale
affective decision-making data (N = 16,337), we introduce a mathematical framework that
bridges two historically separate approaches: one emphasizing internal persistence from affective
science, and the other emphasizing situational reactions from reinforcement learning. Modeling
these together via endogenous (internal momentum) and exogenous inertia (response to external
events) captures affective dynamics that neither alone can explain. The model reveals individual
differences in the sources and mechanisms of affective variability, allowing for a better
understanding of how and why emotions change in dynamic environments.

## Setup
1. Download GBE data from https://datadryad.org/dataset/doi:10.5061/dryad.prr4xgxkk. Load GBE matlab data into the "Data" directory.
2. If using data from the replication experiment, download data from https://osf.io/9g2zw. Move the "Raw Data" folder into the "Data" directory.
3. Install package requirements in Jupyter Notebook and create directories for data and figures:
```
requirements.ipynb
```
4. To run data preprocessing for the GBE and replication datasets, see the "Preprocessing" directory.
5. To fit SINDy and OLS models, see the "Models" directory.
6. To run analysis scripts on model outputs, see the "Analysis" directory.


