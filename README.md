# Population Estimation from Satellite Imagery

Welcome! This is the repository for a full replication set, including code, documentation and data, of my thesis **"Earth Observation for Sustainable Development: A Deep Learning Approach to Urban Population Estimation from Satellite Imagery"** for the Master of Data Science for Public Policy (M.Sc.) at the Hertie School. My thesis was submitted on May 1, 2023.

## Abstract

Knowing where people live is a fundamental question in many allocation and planning decisions in public policy, ranging from urban planning, humanitarian response to the containment of infectious diseases. However, due to limited civil registration systems, accurate population data are scarce, and often scarcest where they are most needed. The increasing availability of satellite imagery, in combination with deep learning, offers a pathway to overcome issues of data scarcity in population mapping.

My thesis introduces a deep learning approach to estimate urban population distribution from satellite imagery where census data is unavailable or costly to obtain. It contributes to a growing field of research on how computer vision and earth observation can be combined to monitor and achieve sustainable development goals. My thesis employs a residual neural network architecture that utilizes publicly available imagery from Sentinel-2 satellites at a resolution of 10m. Using LandScan HD population data from three cities in Ukraine, my thesis marks the first attempt to train a neural network for population estimation across multiple locations and the first application in Eastern Europe. To assess the model’s generalizability, my thesis explores potential sources of bias in population estimation and conducts a transferability experiment outside of the training area.

The results reveal that, when local training data is available, the deep learning model is able to predict population counts with good accuracy that is largely comparable to existing studies. However, its generalizability to unseen data outside of the training area is limited and bias is observed in that the model underestimates densely populated areas and overestimates sparsely populated areas. While my thesis provides recommendations to inform future research, the results demonstrate that satellite imagery can be effective in combination with deep learning to transcend the reliance on census data, provide population mapping services and support policies for sustainable development.

## Deep Learning Framework for Population Estimation

![alt text](https://github.com/f-winkler/pop-estimation/blob/main/figures/framework.png)

## Data for download

Data that was too big to upload on GitHub is available for download here: https://drive.google.com/drive/folders/1umzjgIaTiIUdAdZ708tGPGKW-PAk6bwB?usp=sharing
