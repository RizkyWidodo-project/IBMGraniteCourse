From Feedback to Foresight: An AI-Powered Framework for Analyzing Patient Experience at UnitedHealth Group

Project Overview
This project presents a scalable, AI-driven framework designed to analyze unstructured patient reviews for UnitedHealth Group (UHG). The primary objective is to move beyond generic satisfaction scores and extract granular, actionable insights into the key drivers of patient satisfaction and dissatisfaction.

Background: As one of the world's largest healthcare providers, UHG receives a massive volume of patient feedback across various digital platforms. This unstructured text data is a rich but underutilized resource for understanding the patient experience.

The Problem:
Lack of Specificity: Standard star ratings don't explain why a patient is dissatisfied.
Inability to Scale: Manually reading and categorizing thousands of reviews is operationally unfeasible.
Reactive Problem-Solving: Without specific, real-time insights, UHG can only react to issues after they have already occurred.

Our Approach:
We leveraged the IBM Granite Instruct model to perform Aspect-Based Sentiment Analysis (ABSA). This technique identifies specific topics within a review (e.g., 'customer service', 'waiting time') and assigns a precise sentiment to each one, transforming unstructured complaints into a structured, analyzable database.

Raw Dataset
The analysis was conducted on a representative dataset of 100 patient reviews. The raw data can be found in (https://www.kaggle.com/datasets/joealvarez/healthcare-reviews)

Insights & Findings
The analysis of the dataset revealed a critical level of dissatisfaction across key areas of the patient journey.
Finding 1: Overwhelmingly Negative Overall Sentiment
A staggering 95% of all patient reviews were negative, indicating a systemic issue with the overall patient experience.
Finding 2: Customer Service is the Primary Point of Failure
98% of reviews mentioned customer service, and of those, 93% of the sentiment was negative. This is the most frequently criticized aspect of the patient experience.
Finding 3: Core Medical Satisfaction is Critically Low
81% of reviews discussed medical care, and 91% of this feedback was negative. This suggests that dissatisfaction extends beyond administrative issues and into the core service delivery.
Finding 4: Waiting Time is a Significant Irritant
While mentioned in just under half of the reviews (48%), the sentiment around waiting time was 88% negative, making it a major pain point for those affected.

AI Support Explanation
This project's core innovation lies in its use of a Large Language Model (LLM) to automate and scale the analysis.

Model Used: IBM Granite Instruct
Technique: Aspect-Based Sentiment Analysis
The AI's role was to function as a highly efficient analysis engine. We engineered a specific prompt that instructed the model to read each review and perform a complex, multi-step task:
Identify mentions of pre-defined categories (customer service, waiting time, medical-related satisfaction).
Classify the sentiment for each mentioned category.
Structure the output into a consistent, machine-readable format.
The use of an instruct model like IBM Granite was crucial. It allowed us to move beyond simple sentiment classification (positive/negative) and extract a much richer, multi-dimensional dataset. This AI-powered framework transforms messy, emotional human language into a structured database, enabling quantitative analysis and data-driven decision-making at a scale that would be impossible to achieve manually.
