# Weather Prediction for Rain or Snow in Hungary
## Introduction

Weather prediction is an extremely critical aspect of modern life, influencing various sectors ranging from agriculture to transportation. This is especially true in the case of extreme weather conditions such as rain or snow, which can bring commercial life to a halt. It is therefore essential to have accurate weather forecasts, as they can help individuals and organizations make informed decisions and plan their activities accordingly. This project, "Weather Prediction: Rain or Snow in Hungary," aims to address the challenge of predicting whether it will rain or snow in Hungary based on various meteorological variables.


![Green Minimalist Rain Sounds Music YouTube Thumbnail](https://github.com/shihabmuhtasim/Machinearning-Model-Weather-Prediction-Rain-Snow-/assets/92597456/d71fe53d-2743-4844-9140-20729d701841)


## Project Objectives

The primary objective of this project is to develop a predictive model that can forecast whether a specific location in Hungary will experience rain or snow within a given time frame. By utilizing historical weather data and applying machine learning techniques, we seek to create a model that offers reliable predictions with a high degree of accuracy. This project will contribute to enhancing the precision of weather forecasts, providing valuable insights for individuals, businesses, and authorities in Hungary.

## Problem Statement

Hungary, like many regions, experiences unpredictable weather conditions that can have significant implications for day-to-day activities and planning. Traditional forecasting methods may fall short in providing accurate predictions for rapidly changing weather patterns, particularly in cases of rain and snow. This project addresses the challenge of improving the accuracy of weather predictions for rain and snow, enabling residents, farmers, transportation services, and other stakeholders to make well-informed choices based on reliable forecasts.

## Motivation

The motivation behind this project lies in the potential positive impact on individuals' lives and societal activities. Accurate weather predictions can empower people to optimize their schedules, mitigate risks associated with adverse weather, and even enhance agricultural practices. Additionally, sectors such as transportation and emergency services can benefit from timely information about rain and snowfall, ensuring public safety and efficient resource allocation. By harnessing the power of data and machine learning, this project aims to contribute to the well-being and productivity of Hungary's population.

## Features

- Utilizes historical weather data for Hungary
- Applies machine learning techniques for rain or snow prediction
- Provides accurate forecasts with high precision
- Contributes to informed decision-making for various sectors

## Getting Started
1. Clone this repository.
2. Add data file path to code 3rd cell.
3. Run the main script to train and evaluate the prediction model.

### Models used

**Random Forest:**
- Create a multitude of decision trees, each with its perspective.
- Gather predictions from all trees and select the most common prediction.
- This ensemble approach helps balance out individual weaknesses and provides a robust prediction.

**Gradient Boosting:**
- Begin with an initial decision tree that may have errors.
- Focus on correcting the mistakes made by the initial model.
- Build subsequent models to fix errors of the previous ones, step by step.
- This iterative process improves accuracy over time by refining predictions.

**Decision Tree Classifier:**
- Construct a tree-like model of decisions and their possible consequences.
- Split data into subsets based on conditions that maximize information gain.
- Reach a leaf node that represents a decision or classification.
- Easy to interpret, useful for visualizing decision-making processes.

**Naive Bayes Classifier:**
- Based on Bayes' theorem, a probabilistic approach to classification.
- Assumes features are conditionally independent given the class label.
- Calculates probabilities for different classes based on features.
- Efficient and effective for text classification and simple datasets.

## Results

The project has developed several machine learning models for predicting rain or snow in Hungary. The models include Decision Trees, Random Forest, Gradient Boosting, and Naive Bayes. Each model's performance is evaluated using accuracy, precision, and recall metrics, providing insights into their predictive capabilities.

## Acknowledgments

Special thanks to [Salma Maamouri]([https://www.datascienceuniversity.com/](https://www.kaggle.com/code/salmamaamouri/weather-prediction-regression-neural-model/input)) for providing resources for this project.

## License

This project is done under supervision of Brac University lecturers Sumaiya Akter & Zarin Tahia Hossain.
