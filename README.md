# Project Viewing Options
  1. The best and easiest way to view this project is by viewing the HTML file. If the HTML file isn't rendering in browser, download it and open it.
  2. The 2nd option is to press the '.' key when the repository is open in the browser. This will open the github.dev editor in read-only mode which allows you to view the .ipynb notebook.
  3. The last, more complicated, way of viewing this project is by running the .ipynb notebook yourself. I do not recommend this option if you do not have experience with Jupyter notebooks. First, download the .ipynb file and it's required data file(s) then upload them to Google Colab, and run the notebook. Check to make sure the data file(s) are uploaded into the correct directory on Google Colab or it will not run correctly. Depending on the project, the runtime type might have to be changed.

# Medical Assistant NLP RAG

### Problem Statement

Develop a RAG-based AI system using medical manuals to assist healthcare professionals with diagnostics, treatment, and drug information. The goal is to reduce information overload, improve decision-making speed, and enhance patient outcomes through reliable, accessible knowledge.

### Business Context

The healthcare industry is rapidly evolving, with professionals facing increasing challenges in managing vast volumes of medical data while delivering accurate and timely diagnoses. The need for quick access to comprehensive, reliable, and up-to-date medical knowledge is critical for improving patient outcomes and ensuring informed decision-making in a fast-paced environment.

Healthcare professionals often encounter information overload, struggling to sift through extensive research and data to create accurate diagnoses and treatment plans. This challenge is amplified by the need for efficiency, particularly in emergencies, where time-sensitive decisions are vital. Furthermore, access to trusted, current medical information from renowned manuals and research papers is essential for maintaining high standards of care.

To address these challenges, healthcare centers can focus on integrating systems that streamline access to medical knowledge, provide tools to support quick decision-making, and enhance efficiency. Leveraging centralized knowledge platforms and ensuring healthcare providers have continuous access to reliable resources can significantly improve patient care and operational effectiveness.

**Common Questions to Answer**

**1. Diagnostic Assistance**: "What are the common symptoms and treatments for pulmonary embolism?"

**2. Drug Information**: "Can you provide the trade names of medications used for treating hypertension?"

**3. Treatment Plans**: "What are the first-line options and alternatives for managing rheumatoid arthritis?"

**4. Specialty Knowledge**: "What are the diagnostic steps for suspected endocrine disorders?"

**5. Critical Care Protocols**: "What is the protocol for managing sepsis in a critical care unit?"

### Objective

As an AI specialist, your task is to develop a RAG-based AI solution using renowned medical manuals to address healthcare challenges. The objective is to **understand** issues like information overload, **apply** AI techniques to streamline decision-making, **analyze** its impact on diagnostics and patient outcomes, **evaluate** its potential to standardize care practices, and **create** a functional prototype demonstrating its feasibility and effectiveness.

### Data Description

The **Merck Manuals** are medical references published by the American pharmaceutical company Merck & Co., that cover a wide range of medical topics, including disorders, tests, diagnoses, and drugs. The manuals have been published since 1899, when Merck & Co. was still a subsidiary of the German company Merck.

The manual is provided as a PDF with over 4,000 pages divided into 23 sections.
