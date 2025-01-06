# AI-Driven-Personalized-Marketing-Content-Generation

# Overview
You are tasked with developing an end-to-end solution for generating personalized
marketing content for retail banking customers using transaction data and generative
AI. The solution should demonstrate your ability to handle data processing, customer
segmentation, and content generation using Data Science and Generative AI approches.
# Problem Statement
Create a system that generates personalized marketing emails for bank customers based
on their transaction patterns. The system should:
1. Process transaction data to derive meaningful customer behaviours
2. Segment customers into distinct profiles
3. Generate tailored marketing content including:
o Email body
o Marketing tagline
o Relevant image suggestion

# Data Description
You will receive a sample dataset containing:
• Customer transaction data (anonymized)
• Basic customer information
• Transaction categories, amounts and timestamps

## Steps to run the notebook

1. Unzip Data: Extract the data.zip file and place the 3 data files in the data folder. Use the unzip notebook to upload the data into the folder.
2. Transaction Data Analysis: Run the Transaction_Data EDA.ipynb notebook to analyze transaction data.
3. User Data Analysis: Run the User_Data EDA.ipynb notebook for user data analysis.
4. Feature Engineering: Execute the Data Processing & Feature Engineering.ipynb to generate relevant features for customer segmentation and behavior analysis.
5. Customer Segmentation: Run the Clustering.ipynb notebook to perform clustering and define customer profiles based on the segments.
6. Content Generation: Finally, execute the LLM BASED Content GENERATION.ipynb in Google Colab (ensure runtime is set to T4 GPU) for generating emails, taglines, customer profiles, and Text2Image content. Notebook has multiple examples run as well showchasing LLM model generation [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/username/repository/blob/main/notebook_name.ipynb](https://colab.research.google.com/drive/1Asd_lR6bJ4yYxhgRCtjrr6IqkVltGoKa?usp=sharing))

