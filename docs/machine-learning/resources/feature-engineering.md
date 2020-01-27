---
title: Feature engineering with ML.NET
description: Learn how to engineer features from your data with ML.NET
ms.topic: concept
ms.date: 01/24/2020
---

# Feature engineering with ML.NET

Before data can be trained with an ML.NET machine learning algorithm, it needs to be transformed into **features**. Features are numbers that optimally represent the patterns in your data. These patterns are identified and parameterized by an ML.NET algorithm to build a model that can make prediction with previously unseen data. The process of transforming raw input data into features is called **feature engineering**. Data suitable as input to a machine learning algorithm are referred to as **feature vectors**.

There are multiple ways that your data might need be engineered into features:

* convert categorical data into numbers
* convert text data into numbers
* convert image data into numbers
* scale and normalize numerical data
* drop data columns that do not contain information relevant to the model

All feature engineering in ML.NET is performed using transforms. Transforms can be chained together to perform multiple feature engineering operations. This article describes which transforms to use for the different feature engineering operations.
