# **Grant Title Generation Using Generative Models**

This repository contains the code and resources for the project **"Generating Grant Titles from Research Paper Abstracts Using Generative Models"**. The project focuses on automating the creation of grant titles from research paper abstracts using pre-trained generative models such as **T5** and **BART**.

---

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Data Description](#data-description)
4. [Setup Instructions](#setup-instructions)
5. [Usage](#usage)
   - [Data Preprocessing](#data-preprocessing)
   - [Model Fine-Tuning](#model-fine-tuning)
   - [Evaluation](#evaluation)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

---

## **Overview**
Grant writing is a challenging process that involves crafting concise and impactful titles. This project leverages natural language processing (NLP) techniques to fine-tune pre-trained models to generate grant titles from research paper abstracts.

### **Key Objectives**
- Automate the generation of grant titles.
- Enhance accessibility for non-native English speakers.
- Improve the clarity and impact framing of grant proposals.

---

## **Features**
- Preprocessing pipeline for cleaning and tokenizing text data.
- Fine-tuning scripts for **T5-small** and **BART-base** models.
- Evaluation metrics: **ROUGE**, **BERTScore**, and **BARTScore**.
- Visualization of evaluation results (score distributions, scatter plots, etc.).

---

## **Data Description**
The dataset consists of research paper abstracts and corresponding grant titles extracted from:
- **SciSciNet**: Research abstracts and metadata.
- **Semantic Scholar API**: Titles and abstracts matched via DOI.

### **Fields in the Dataset**
- `doi`: Unique identifier for each paper.
- `abstract`: Research paper abstracts.
- `title`: Corresponding grant titles.
- `nsf_frequency`: Frequency of NSF funding mentions.

---

## **Setup Instructions**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/grant-title-generation.git
   cd grant-title-generation
