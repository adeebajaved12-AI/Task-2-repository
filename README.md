#  Smart University FAQ Chatbot (AI Support System)
**CodeAlpha Artificial Intelligence Internship - Task 2**

##  Project Description
This repository contains a streamlined, AI-powered FAQ Chatbot developed for the **University of Kotli Azad Jammu and Kashmir (UOK AJ&K)**. The goal of this project is to automate student support by providing instant, accurate responses to common queries regarding admissions, examinations, hostels, and campus facilities.

By leveraging **Natural Language Processing (NLP)**, this chatbot goes beyond simple keyword matching to understand the semantic intent behind a user's question.

##  Key Features
The project is built to fulfill all the technical requirements of the internship task:

* **Comprehensive FAQ Collection:** Covers a wide range of university-related topics including Admissions, Transport, Hostels, and Degree Verification.
* **NLP Preprocessing (via NLTK):**
    * **Lowercasing & Cleaning:** Removing special characters and noise.
    * **Tokenization:** Breaking sentences into meaningful units using NLTK.
    * **Stopwords Removal:** Filtering out common words (e.g., 'the', 'is') to focus on key information.
* **Semantic Matching Logic:**
    * Uses **Sentence-Transformers** (`all-MiniLM-L6-v2`) to convert text into high-dimensional vectors (Embeddings).
    * Implements **Cosine Similarity** to calculate the mathematical distance between user queries and the FAQ database for high accuracy.
* **Modern UI:** A professional and interactive chat interface built using **Gradio**, featuring custom themes and example prompts for better user experience.

##  Installation & Usage

### 1. Requirements
Ensure you have Python installed. The following libraries are required:
`gradio`, `sentence-transformers`, `nltk`, `torch`.

### 2. Running the Project
1. Open the `FAQ_Chatbot.ipynb` file in Google Colab.
2. Run all cells sequentially.
3. Access the chatbot via the generated public `gradio.live` link.

---
**Developed by:** Adeeba Javed

**University:** University of Kotli Azad Jammu and Kashmir  
**Domain:** Artificial Intelligence  
**Organization:** CodeAlpha
