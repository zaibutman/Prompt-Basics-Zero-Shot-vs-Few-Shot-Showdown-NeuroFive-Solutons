# Prompt Basics — Zero-Shot vs Few-Shot Showdown

## Week 1 – Generative AI & Prompt Engineering

### Overview

This project is part of my **Generative AI & Prompt Engineering Internship** at **NeuroFive Solutions**.

The objective of this assignment is to explore one of the fundamental concepts of prompt engineering: **Zero-Shot Prompting** and **Few-Shot Prompting**. The experiment demonstrates how providing examples within a prompt can improve the consistency and accuracy of Large Language Models (LLMs) when performing a text classification task.

---

## Objective

The primary goals of this project are to:

* Understand the difference between Zero-Shot and Few-Shot prompting.
* Evaluate how prompt design influences AI-generated responses.
* Compare the performance of multiple AI models on the same classification task.
* Learn how examples improve model understanding and output consistency.

---

## Problem Statement

Classify **10 customer support messages** into one of the following categories:

* Complaint
* Question
* Praise

The same dataset is evaluated using two different prompting techniques:

1. **Zero-Shot Prompting**
2. **Few-Shot Prompting**

The results are then compared across different AI models.

---

## Technologies & AI Models

This project can be tested using any modern Large Language Model, including:

* ChatGPT
* Claude
* Gemini

---

## Prompting Techniques

### Zero-Shot Prompting

The AI receives only the task instructions without any examples.

**Purpose**

* Measure the model's ability to complete the task using only its pre-trained knowledge.
* Establish a baseline for comparison.

---

### Few-Shot Prompting

The AI receives the same task instructions along with a few labeled examples before processing the actual dataset.

**Purpose**

* Provide context about the expected behavior.
* Reduce ambiguity.
* Improve consistency and classification accuracy.

---

## Project Structure

```text
Prompt-Basics-ZeroShot-vs-FewShot/
│
├── LICENSE
├── README.md
├── .gitignore
├── requirements.md
│
├── prompts/
│   ├── zero_shot_prompt.txt
│   └── few_shot_prompt.txt
│
├── dataset/
│   └── customer_support_messages.md
│
├── results/
├── chatgpt_results.md
├── claude_results.md
├── gemini_results.md
└── comparison_table.md



---

## Workflow

1. Prepare a dataset of customer support messages.
2. Create a Zero-Shot prompt.
3. Test the prompt using multiple AI models.
4. Create a Few-Shot prompt with labeled examples.
5. Test the same dataset again.
6. Compare the outputs.
7. Analyze the differences.
8. Summarize the findings.

---

## Evaluation Criteria

The comparison focuses on:

* Classification accuracy
* Response consistency
* Understanding of task instructions
* Overall reliability

---

## Key Learning Outcomes

Through this assignment, I learned that:

* Prompt wording significantly impacts AI responses.
* Examples help models understand the desired output format.
* Few-Shot Prompting generally produces more reliable and consistent results than Zero-Shot Prompting.
* Effective prompt engineering is about providing clear instructions and sufficient context rather than simply asking a question.

---

## Results Summary

The experiment compares the performance of different AI models using both prompting techniques.

| AI Model | Zero-Shot      | Few-Shot|
| -------- | -------------  | -------------|
| ChatGPT  | *09/10*   | *10/10* |
| Claude   | *10/10*   | *10/10* |
| Gemini   | *09/10*   | *10/10* |


---

## Conclusion

This project demonstrates the practical value of prompt engineering in improving AI performance. While Zero-Shot Prompting is effective for straightforward tasks, Few-Shot Prompting provides additional context through examples, resulting in greater accuracy, consistency, and reliability across different Large Language Models.

The experiment highlights that carefully structured prompts are an essential component of building dependable AI-powered applications.

---

## Author

**Shah Mubarak Zaib**

BS Computer Science Student
AI & Prompt Engineering Enthusiast
AI/ML Intern | Prompt Engineer | Python Developer

---

## Acknowledgements

This project was completed as part of the **Week 1 – Generative AI & Prompt Engineering Internship Program** at **NeuroFive Solutions**.

Special thanks to the mentors and the NeuroFive Solutions team for designing practical, hands-on assignments that strengthen real-world prompt engineering skills.
