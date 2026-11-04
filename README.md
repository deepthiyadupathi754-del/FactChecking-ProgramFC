# Fact-Checking Complex Claims with Program-Guided Reasoning

## 1. Project Overview
This project demonstrates fact-checking of complex claims using ProgramFC (Program-Guided Reasoning). It uses the HOVER dataset and the FLAN-T5-small model to verify claims based on supporting evidence.

## 2. Objectives
- Understand program-guided reasoning for fact-checking.
- Execute the ProgramFC framework.
- Verify complex claims using evidence.
- Evaluate the prediction results.

## 3. Technologies Used
- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- FLAN-T5-small
- HOVER Dataset
- Scikit-learn
- GitHub

## 4. Dataset
**HOVER (A Dataset for Many-Hop Fact Extraction and Claim Verification)**

A sample from the HOVER development dataset was used for the demonstration.

## 5. Implementation
The project was executed using Google Colab.

Adaptations made for the current environment:
- CPU execution instead of model parallelization.
- Lazy loading of the Pyserini retriever for gold-setting execution.
- Updated prediction parsing.
- Updated evaluation code for compatibility with the installed Scikit-learn version.
- FLAN-T5-small was used for CPU-based execution.

## 6. Execution Configuration

| Parameter | Value |
|---|---|
| Dataset | HOVER |
| Model | FLAN-T5-small |
| Setting | Gold |
| Device | CPU |
| Test samples | 1 |

## 7. Results
The demonstration successfully executed one manually prepared fact-checking program.

- Gold label: supports
- Predicted label: supports
- Correct prediction: Yes
- Demonstration accuracy: 100% (1 out of 1 sample)

Note: This is a one-sample demonstration and does not represent full-dataset benchmark performance. The program was manually prepared; automatic program generation was not evaluated.
## 8. Screenshots

### 1. Dataset and Sample Program
![Dataset and Program](./dataset_program.png)

### 2. Model Execution Summary
![Model Execution](./model_execution.png)

### 3. Evaluation Results
![Evaluation Results](./evaluation_results.png)

### 4. Saved Prediction
![Saved Prediction](./saved_prediction.png)
## 9. Conclusion
The demonstration illustrates how program-guided reasoning can be used to break down a complex claim into smaller verification steps and generate a final prediction using supporting evidence.

## 10. Original Repository
https://github.com/mbzuai-nlp/ProgramFC

## 11. Project Files
The repository contains the adapted Python source files, Google Colab notebook, sample program, and execution screenshots.
