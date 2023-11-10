# Resume-Extraction
Project Lifecycle Documentation
This documentation provides an overview of the "Resume Extraction" project, including the project plan, deliverables, and the lifecycle of the project. It outlines the tasks and objectives for each week, along with the corresponding deliverables.

## Table of Contents
- Introduction
- Project Plan: Resume Extraction
- Project Lifecycle
- Summary

## 1. Introduction
The "Resume Extraction" project aims to automate the process of extracting relevant information from resumes using Named Entity Recognition (NER) techniques. By leveraging NER models in Natural Language Processing (NLP), the project aims to simplify the resume shortlisting process for HR professionals, improving efficiency and reducing manual effort.

## 2. Project Plan: Resume Extraction
The project plan is divided into seven weeks, with each week focusing on specific tasks and deliverables. The plan encompasses the entire lifecycle of the project, from problem understanding to final reporting and submission.

### Week 7: Problem Understanding and Data Collection
In this week, the project team defines the problem statement and objectives of the project. They conduct research on existing NER models and techniques for resume extraction and understand the given dataset. Additionally, the team sets up a version control system and creates a project repository.

Deliverables:
- Problem statement, business understanding, and objectives document.


### Week 8: Data Preprocessing
During this week, the team defines the entity categories to be extracted from the resumes. They annotate the collected resumes with the corresponding entity labels to enable the NER model's training. The team ensures consistency and quality in the annotation process.

Deliverables:
- Data Preprocessing dataset of resumes.

### Week 9: Named Entity Recognition (NER)
In Week 9, the team explores different NER techniques and models suitable for resume extraction. They preprocess the annotated dataset, including tokenization, normalization, and handling of special characters. The preprocessed dataset is split into training, validation, and testing sets. The team then implements and trains an NER model using the training dataset, considering architectures like Bidirectional LSTM-CRF or Transformer-based models. They fine-tune the model's hyperparameters and optimize its performance.

Deliverables:
- Trained NER model.
- Preprocessed dataset split into training, validation, and testing sets.

### Week 10: Performance Evaluation & Reporting
During this week, the team evaluates the NER model's performance using the validation dataset, measuring metrics such as precision, recall, and F1-score. They analyze the model's strengths and weaknesses and iteratively improve it by adjusting the architecture, hyperparameters, or training strategy. A performance evaluation report is generated, summarizing the results and providing insights into the model's performance and limitations.

Deliverables:
- Model evaluation results.
- Performance evaluation report.

### Week 11: Model Deployment
In Week 11, the team develops a Flask web application that allows users to upload resumes for information extraction using the trained NER model. They implement the necessary backend functionality for processing resume files and applying the NER model for entity extraction. Additionally, the team sets up a deployment environment, such as Heroku, and deploys the Flask application to a web server.

Deliverables:
- Flask application code.
- Deployed web application.

### Week 12: Model Inference and Refinement
During this week, the team tests the deployed web application by uploading sample resumes and extracting entities using the NER model. They collect user feedback and incorporate improvements based on usability and performance. Any necessary refinements or enhancements to the NER model are made based on the insights gained from real-world usage.

Deliverables:
- Refined Flask application.
- Updated NER model (if applicable).

### Week 13: Final Reporting and Submission
In the final week, the team prepares the final project report, including an overview, methodology, results, and future recommendations. They create a presentation summarizing the project's objectives, approach, key findings, and potential applications. The team practices and refines the presentation before submitting the final project report, along with the code and presentation.

Deliverables:
- Final project report.
- Presentation slides.
- Submitted project report, code, and presentation.

## 3. Project Lifecycle
The project lifecycle spans thirteen weeks, starting with problem understanding and data collection and concluding with final reporting and submission. Each week focuses on specific tasks and deliverables, contributing to the overall objective of automating the resume extraction process.

## 4. Summary
The "Resume Extraction" project aims to automate the process of extracting relevant information from resumes using Named Entity Recognition (NER) techniques. The project plan outlines the tasks and deliverables for each week, covering problem understanding, data preprocessing, NER model development, performance evaluation, model deployment, and refinement. The project lifecycle spans thirteen weeks, providing a structured approach to effectively tackle the resume extraction problem and enhance HR efficiency through automation.

## Installation
* Environment Initialization : conda create -p venv python==3.10 -y
* Install Packages : pip install -r requirements.txt
