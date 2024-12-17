

# 📚 **Portuguese Medical Knowledge Dataset and Question Classifier**  

This repository contains the **Teste de Progresso (TP) dataset**, a curated collection of Portuguese-language multiple-choice medical questions, along with the code for a machine learning-based question classifier. The dataset and accompanying tools are designed to support AI research, benchmarking, and applications in medical education, particularly in **non-English medical contexts**.

---

## 🚀 **Overview**  

Artificial Intelligence (AI) models, particularly large language models (LLMs) like ChatGPT, have shown remarkable capabilities in addressing complex tasks. However, existing benchmarks primarily focus on **English-language datasets**, leaving a critical gap in multilingual AI evaluation.  

To address this, we introduce:  

1. **A curated dataset** from the *Teste de Progresso* (TP), a widely used Brazilian progress test to assess medical knowledge.  
2. **Code for a medical question classifier** based on the BERTimbau model, capable of categorizing questions into six key medical domains.  

---

## 📊 **Dataset Details**  

The dataset consists of:  
- **720 multiple-choice questions** collected from TP exams over five years (2019–2023).  
- Questions evenly distributed across six primary medical domains:  
  - **Basic Sciences**  
  - **Internal Medicine**  
  - **Surgery**  
  - **Obstetrics and Gynecology**  
  - **Public Health**  
  - **Pediatrics**  

The dataset is provided in **CSV format** with the following fields:  
- `question_text`: Text of the multiple-choice question.  
- `correct_answer`: The correct alternative.  
- `medical_domain`: The corresponding medical subject area.  

---

## 🛠️ **What’s Included**  

### 1. **The Dataset**  
The cleaned and structured TP dataset for use in AI benchmarking and classification tasks.  

### 2. **Question Classifier Code**  
We provide the implementation of a **BERTimbau-based model** for classifying medical questions into their respective domains.  
- **Training and evaluation code** is included.  
- Preprocessing and model fine-tuning steps are fully documented for reproducibility.  

---

## 🔍 **Applications**  

The dataset and tools can be used for:  
- **Benchmarking LLM performance** (e.g., GPT-4) on Portuguese medical knowledge questions.  
- **Automated classification** of medical questions into specific domains.  
- Supporting AI research focused on multilingual medical education and knowledge assessment.  

---
## 📈 **Performance**  

### GPT-4 Benchmarking Results  
Using the TP dataset, GPT-4 achieved an **overall accuracy of 90%** across the six medical domains:  

| **Domain**                | **Accuracy** |  
|---------------------------|--------------|  
| Basic Sciences            | 85%          |  
| Internal Medicine         | 100%         |  
| Surgery                   | 90%          |  
| Obstetrics and Gynecology | 95%          |  
| Public Health             | 80%          |  
| Pediatrics                | 85%          |  

### Question Classifier Results  
The BERTimbau-based classifier achieved an overall accuracy of **94%**, demonstrating strong performance across all domains.

---

## 📄 **Citation**  

If you use this dataset or code, please cite our work:  

```bibtex
@article{your_paper_reference,
  title     = {Portuguese Medical Knowledge Dataset and Question Classifier},
  author    = {Your Names},
  journal   = {Journal/Conference Name},
  year      = {2024},
  doi       = {10.xxxx/xxxx}
}
```

---

## 🤝 **Contributions**  

We welcome contributions to improve the dataset, models, or documentation. Please submit a pull request or open an issue.

---

## 📧 **Contact**  

For questions or collaborations, reach out to:  
- **Henrique Onaga**  
- **henrique.onaga@aluno.fcmsantacasasp.edu.br**  

