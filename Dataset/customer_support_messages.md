# Customer Support Messages Dataset

## Overview

This dataset contains **10 customer support messages** used to evaluate the performance of Large Language Models (LLMs) using two prompt engineering techniques:

- Zero-Shot Prompting
- Few-Shot Prompting

Each message belongs to one of three predefined categories:

- **Complaint** – The customer expresses dissatisfaction, frustration, or reports a problem.
- **Question** – The customer requests information or asks for assistance.
- **Praise** – The customer expresses satisfaction, appreciation, or positive feedback.

---

## Dataset

| Message No. | Customer Support Message | Expected Category |
|-------------|--------------------------|-------------------|
| 1 | I ordered my package five days ago and it still hasn't arrived. This is unacceptable. | Complaint |
| 2 | Can I change my delivery address after placing an order? | Question |
| 3 | Your support team solved my issue within minutes. Excellent service! | Praise |
| 4 | The app keeps crashing every time I try to log in. | Complaint |
| 5 | Do you offer discounts for students? | Question |
| 6 | Thank you for the quick refund process. I really appreciate it. | Praise |
| 7 | I was charged twice for the same purchase. | Complaint |
| 8 | How can I reset my password? | Question |
| 9 | I'm really impressed with the product quality. | Praise |
| 10 | The customer service representative was rude and unhelpful. | Complaint |

---

## Category Distribution

| Category | Count |
|----------|------:|
| Complaint | 4 |
| Question | 3 |
| Praise | 3 |
| **Total Messages** | **10** |

---

## Classification Guidelines

### Complaint
A message should be classified as **Complaint** if the customer:

- Reports a problem or issue.
- Expresses dissatisfaction or frustration.
- Mentions poor service or product quality.
- Requests resolution for a negative experience.

---

### Question
A message should be classified as **Question** if the customer:

- Requests information.
- Asks how to perform an action.
- Seeks clarification about a product or service.
- Inquires about policies or features.

---

### Praise
A message should be classified as **Praise** if the customer:

- Expresses satisfaction.
- Appreciates a product or service.
- Compliments customer support.
- Shares a positive experience.

---

## Purpose

This dataset is designed for educational purposes to compare the effectiveness of **Zero-Shot Prompting** and **Few-Shot Prompting** in customer support message classification.

The same dataset is evaluated across multiple Large Language Models, allowing a fair comparison of prompt engineering techniques and model performance.

---

## Author

**Shah Mubarak Zaib**

Generative AI & Prompt Engineering Intern  
NeuroFive Solutions