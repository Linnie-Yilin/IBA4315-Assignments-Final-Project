
# IBA4315 Advanced AI in Application: Assignments and Final Project

## Introduction
This document provides an overview of the assignments and final project for the CUHKSZ course IBA Advanced AI in Application (Spring 2024). The course covers practical AI applications, focusing on real-world problem-solving with advanced AI models and techniques.

---

## Assignments

### A1 - Bank Account Application Fraud and Airbnb Review Analysis
This assignment consists of two parts:
1. **Bank Account Application Fraud**: Focuses on detecting fraudulent activities in bank account applications using machine learning techniques. Students analyze a dataset, handle imbalanced data, and build a predictive model to classify applications as legitimate or fraudulent.
2. **Airbnb Review Analysis**: Explores sentiment analysis on Airbnb reviews. Students preprocess textual data, perform exploratory analysis, apply sentiment classification, and generate actionable insights.

### A2 - Customer Churn Prediction
This assignment focuses on building a predictive model to identify bank customers at high risk of churning using the **`Churn_Modeling.csv`** dataset. Students preprocess data, perform exploratory analysis, and develop machine learning models to improve retention strategies.

### A3 - LLM-powered Applications with APIs
This assignment involves building applications powered by large language models (LLMs) using APIs. Students develop:
1. A **review analyzer** to classify and summarize customer reviews.
2. A **course bot** to answer FAQs about the course syllabus, assignments, and policies.

### A4 - Fine-tune a LLM using Colab and LLaMA-Factory
This assignment focuses on fine-tuning a pre-trained large language model using the LLaMA-Factory framework in Colab. Students fine-tune a model on a domain-specific dataset, such as financial exams, while optimizing for resource limitations.

---

## Final Project: Travel Insurance Recommendation AI Agent

### Introduction
This project will design a new Al system to predict flight delays and price the insurance, enabling the airlines to provide personalized insurance recommendations for passengers. This Al system will analyze the rates of flight delays based on multiple relevant data, such as flight dynamic data, city weather, and special situations data. Besides, it will construct user profiles with sentiment analysis based on users' feedback to airlines. Finally, the system will offer personalized and optimal insurance recommendations, contributing to supplying a suitable service for each customer and gaining more benefits for airlines. Through personalized insurance recommendations, our AI system can boost customer satisfaction and loyalty while reducing stress caused by flight delays. Our system could reshape customer service in the airline industry and promote a positive image and competitive edge for airlines, resulting from focusing on prediction accuracy and user interaction quality.

---

### Dataset
The project utilizes the following datasets:

- [Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment?resource=download&select=Tweets.csv): Sentiment data from Twitter related to airlines.
- [InsuranceCorpus](https://huggingface.co/datasets/Ddream-ai/InsuranceCorpus): A comprehensive corpus for insurance-related NLP tasks.
- [United States Department of Transportation](https://www.transtats.bts.gov/databases.asp?Z1qr_VQ=E&Z1qr_Qr5p=N8vn6v10&f7owrp6_VQF=D): Transportation datasets for flight details and delays.

---

### Framework

#### Overall AI-driven Framework
![AI-driven Framework](assest/image.png)

#### Deep Learning Model: ASTGCN
The deep learning component leverages the Adaptive Spatio-Temporal Graph Convolutional Network (ASTGCN) framework. This model captures temporal and spatial correlations in the data for precise flight delay predictions.

![ASTGCN Architecture](assest/ASTGCN.png)

---

### Project Details
- **Report**: [Travel Insurance Recommendation AI System Based on Flight Delay Predictions and Customer Sentiment](assest/report.pdf)
- **Presentation**: [Project Presentation](https://cuhko365-my.sharepoint.com/:p:/g/personal/121020064_link_cuhk_edu_cn/EeZSiXgHQB9Dq-2wFqcVypUBuUREppF42pGmyjBsHWRVqw)

---

This README outlines the key components of the course and the final project, providing a comprehensive summary of the work completed during the semester.
