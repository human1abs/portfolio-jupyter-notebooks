# Portfolio
Welcome to my brand-new AI/ML-related portfolio. 

## [1. Cinematic Storyboards](Cinematic-Storyboards-with-SDXL.md)
The project I'm most proud of is the pipeline for creation of [Cinematic Storyboards (open in Colab)](https://colab.research.google.com/drive/18adY8WtK91mCePVD3BJv2kmPQmunPqf0?usp=sharing). This project presents Cinematic Storyboards - a new way to create storyboards for the film and video industry which has the potential to make them more authentic to the true concept of the authors and to dramatically cut time and cost for their making. All that is made possible by utilising the benefits of the Stable Diffusion XL model (and with a little help from the HuggingFace ecosystem).

Cinematic Storyboards is an upgrade of the current state of affairs of storyboard making because it is much more flexible and available for customisation. By implementing simple Low-Rank Adaptation (LoRA) and fine-tuning (Dreambooth) techniques, we are now ready to create storyboards which are much more connected to the specifics of the videomaking project and the ideas behind it. 

## [2. Skin Cancer Detection with CNNs](CNN-skin-cancer-detection.ipynb)
This project aims at searching for reliable ways to signal for malignant skin developments of the melanoma type by the means of Machine Learning and Deep Neural Networks methodologies, utilising the knowledge gained during SoftUni's Machine Learning course. 

I used a free dataset published in Kaggle. The dataset contains images with a total size of around 1.5GB. If for some reason it's not convenient to download them from Kaggle, here's a link to them stored in my personal Google Drive. Here, you will also find saved versions of the final two models presented in this paper (complete with their training history) - as there was not enough space for all the models to be uploaded along with the paper.

The possibility to determine malignant melanoma with a reliable degree of probability, based only on a photo complete with basic personal data, presents people with the amazing opportunity to get medical diagnosis while the cancer development is still at its early stages - which are related to significantly higher survival rates.

## [3. ATE of Diets on Weight Loss and Counterfactual Analysis](ATE-Counterfactual-Analysis-Diets.ipynb)
The goal of this project is to estimate the Average Treatment Effect of diets on weight loss using a real-world dataset (as opposed to fictional data created in doWhy) by using a Structural Causal Model.

Furthermore, the we implement Counterfactual Analysis in order to calculate how the weights of participants would have change if they would have chosen a different diet.

## [4. Analysis of Stock-Price Time Series via Granger Causality](Stock-Price_Analysis-Granger-Causality.ipynb)
Granger causality occurs when events from a particular time series influence events from another time series happening at later points in time. It was developed by Clive Granger in 1969 as a tool to analyse cases and perform predictions in the field of economics. Nowadays, Granger causality is used in other fields, too - such as neuroscience.

Let's take a look at one example. As copper is typically used for the production of wires and connectors in mobile phones, let's investigate whether the movements of the stock price of copper Granger-cause the change in the stock price of famous smartphone producer Apple.
