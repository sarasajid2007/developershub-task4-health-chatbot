#  Task 4: General Health Query Chatbot

This repository contains my submission for **Task 4: General Health Query Chatbot** as part of the **DevelopersHub AI/ML Internship**.

##  Project Overview

The objective of this project is to build an AI-powered chatbot that provides general health-related information using a Large Language Model (LLM). The chatbot uses the Hugging Face **FLAN-T5** model along with prompt engineering and safety filtering to deliver clear, concise, and responsible health guidance.

The chatbot is designed for informational purposes only and does not diagnose medical conditions or prescribe medications.

---

##  Objectives

- Build a health information chatbot using a Hugging Face LLM.
- Apply prompt engineering for accurate responses.
- Implement safety filters to prevent harmful interactions.
- Provide short and user-friendly health information.
- Create an interactive command-line chatbot.

---

##  Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- FLAN-T5 (google/flan-t5-base)
- PyTorch
- SentencePiece

---

##  Project Structure

```
developershub-task4-health-chatbot/
│
├── General_Health_Query_Chatbot.ipynb
├── README.md
└── images/
```

---

##  Model Used

- **Model:** Google FLAN-T5 Base
- **Framework:** Hugging Face Transformers
- **Task:** Text-to-Text Generation

The chatbot uses prompt engineering to generate informative health-related responses while avoiding medical diagnosis or prescriptions.

---

##  Features

- General health question answering
- Prompt engineering for better responses
- Safety keyword filtering
- Interactive chatbot interface
- Lightweight implementation
- Easy to extend for future improvements

---

##  Safety Features

The chatbot includes a safety filter that detects harmful or crisis-related queries such as:

- Suicide
- Self-harm
- Overdose
- Harming oneself

Instead of generating unsafe responses, it encourages users to seek help from healthcare professionals or emergency services.

---

##  Example Questions

You can ask questions such as:

- What causes a sore throat?
- How can I prevent dehydration?
- Is paracetamol safe for children?
- What are the symptoms of the common cold?
- What foods are rich in Vitamin C?

---

##  How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/developershub-task4-health-chatbot.git
```

### Install dependencies

```bash
pip install transformers==4.41.2 torch accelerate sentencepiece
```

### Run the notebook

Open the notebook in **Google Colab** or **Jupyter Notebook** and execute all cells.

---

## 📷 Sample Output

The chatbot can answer general health questions such as:

**User:**

```
What causes a sore throat?
```

**Bot:**

```
A sore throat is commonly caused by viral infections, allergies, or irritation. If symptoms persist or become severe, consult a healthcare professional.

Note: This is general health information and is not a substitute for professional medical advice.
```

---

##  Learning Outcomes

Through this project, I learned:

- Prompt Engineering
- Hugging Face Transformers
- Working with Large Language Models (LLMs)
- Building AI-powered chatbots
- Safety filtering for conversational AI
- Interactive command-line applications

---

##  Author

**Sara Sajid**

BBA Student | Social Media Marketer | AI & Machine Learning Enthusiast

---

##  Internship

**DevelopersHub Corporation**

AI & Machine Learning Internship Program

---

##  License

This project is developed for educational purposes as part of the DevelopersHub AI/ML Internship.

---

##  Acknowledgements

- DevelopersHub Corporation
- Hugging Face
- Google FLAN-T5
- PyTorch
- Python Community
- Google Colab
