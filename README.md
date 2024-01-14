# Automatic Customer Ticket Classification

This repository belongs to Team 3 for KAIST CS372 Natural Language Processing with Python course.

## Introduction

This project introduces an automated ticket classification system using Natural Language Processing (NLP) with Python's NLTK library. The goal is to streamline customer service by automatically categorizing support tickets into specific classes such as 'Issue', 'Refund', and 'Feedback'. This approach aims to improve response times and overall efficiency by identifying the main topic, recognizing the product referenced, suggesting a response type, and generating a concise summary of the complaint. The system's automation could potentially lead to quicker issue resolution, reducing the need for extensive human intervention and enhancing overall customer satisfaction.

## Dataset
The dataset for this project, sourced from Kaggle's "[Automatic Ticket Classification](https://www.kaggle.com/datasets/venkatasubramanian/automatic-ticket-classification)" by Venkatasubramanian Sundaramahadevan, comprises 78,313 customer complaints from a financial company, featuring 22 attributes. The relevant columns extracted for analysis are: `complaint`, `company_response`, and `product`. This dataset has found applications in NLP and Text Mining research and is a valuable resource for our project.

## Result

The system seamlessly integrates into existing workflows, accessible through a dedicated API or user-friendly web interface. Users input text data, such as queries or complaints, and the system provides the following outputs to aid agents in quick and accurate responses:
1. **Topic Classification:** Swiftly categorizes tickets for efficient understanding and response. Allows for easy delegation to specialized agents.
2. **Product Identification:** Enables detailed problem classification, enhancing response accuracy.
3. **Text Summarization:** Distills lengthy messages to core content, providing agents with a quick overview.
4. **Response Suggestions:** Generates recommended responses, reducing agent effort and automating resolution for trivial issues.
