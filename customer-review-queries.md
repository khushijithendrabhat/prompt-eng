1. Problem Statement: Customer Query Classification Using Prompt Engineering
An e-commerce company receives numerous customer queries related to orders,
deliveries, payments, refunds, cancellations, and product defects. Your task is to design
an effective prompt that classifies each customer query into the appropriate predefined
category. 

soln:


Writing

You are a sentiment analysis system. Your task is to analyze the customer's review and classify its overall sentiment into one of the following three categories:

- Positive
- Negative
- Neutral

Instructions:

1. Read and understand the customer review carefully.
2. Identify the overall sentiment expressed by the customer.
3. If the review expresses satisfaction, happiness, or praise, classify it as Positive.
4. If the review expresses dissatisfaction, disappointment, or complaints, classify it as Negative.
5. If the review contains only factual information without expressing any clear emotion or opinion, classify it as Neutral.
6. If the review contains both positive and negative sentiments, classify it based on the overall sentiment.

Input: A customer review in natural language.

Output: Return exactly one word from the following options: Positive Negative Neutral

Do not provide explanations, justifications, punctuation, or any additional text. Output only the sentiment category.

