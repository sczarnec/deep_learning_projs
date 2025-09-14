# Deep Learning Projects

This repo contains a variety of projects from a Designing Human-Centered AI PhD class, which mainly involved deep learning-based projects. Descriptions of the projects are listed here along with two of the notebooks.

<br>

## CNNs for Pneumonia Predictions using X-Rays

This project involved using unstructured image data to predict whether a person has pneumonia based on X-ray images. We were given a basic CNN architecture along with a Kaggle dataset and were tasked with tuning the architecture to achieve better Kaggle test results. This involved trying out things like combinations of different layers, regularization methods (batch normalization, dropout), learning rates, and more. Unfortunatelty, I lost the notebook but wanted to mention the project.

<br>

## Genetic Algorithm for Phishing Model Hyperparameter Tuning

This project involved using a biological-based genetic algorithm technique to find the best hyperparameters for an XGBoost model. The model uses structured data to predict whether a given person will click on a phishing link or not. The goal here is to find the best combination of hyperparameters in terms of validation AUC. Although this method likely overfits on that validation data, the goal was to learn how to use a genetic algorithm technique to optimize model performance.

The GA file is in this repo. The final report can be found at .

<br>

## Sentiment Analysis Predictions using NLP Models

This project involved finding the model architecture that achieved the best accuracy on an NLP problem that predicted high or low severity messages of customers. We were given an initial notebook with structured NN, word CNN, character CNN, and LSTM architectures. We were encouraged to try concatenating the dense layers in different architectures for a concatenated model as well as try basic ensembling techniques. We were also encouraged to try transfer learn using transformer models.

In the end, a BERT-based model (fine-tuned version for medical data called Roberta) and the concatenated model were ensembled to achieve the best results. Final results can be seen at .


