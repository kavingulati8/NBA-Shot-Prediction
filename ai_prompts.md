# AI Usage Log – NBA Shot Prediction Project

## Overview

Throughout this project, I used ChatGPT to help me understand different parts of the machine learning process. I mainly used it for guidance when working with the dataset, understanding code, evaluating models, fixing errors, and preparing my final submission. I also used Claude to help format my project report and this log.

I worked in Google Colab, where I ran the code, examined the outputs, and compared the results.

*All prompts below are copied exactly as I typed them.*

---

## 1. Understanding the Dataset

**What I needed help with:**

When I first started the project, I wasn't sure how to begin or how to approach the dataset.

**Prompts I used:**

- "i just opened the github but i havent done anything what is the first step i should take when starting this project"
- "Start from the very beginning and walk me through everything"

**How I used ChatGPT:**

ChatGPT helped me get started with the project, load the training and testing datasets, and examine the available information. I explored factors such as shot distance, defender proximity, and shot type to understand what could influence whether a shot was made.

---

## 2. Building the Machine Learning Model

**What I needed help with:**

I needed guidance on using the dataset to train a model that could predict the probability of a shot being successful.

**AI assistance received:**

I used ChatGPT for step-by-step guidance on selecting features, preparing the data for machine learning, and implementing classification models in Python.

**How I used ChatGPT:**

ChatGPT helped me understand how Gradient Boosting works and how to train a model using Scikit-learn. I ran the code in Google Colab and examined the predictions and results.

*Prompts from this stage are still being retrieved from my conversation history.*

---

## 3. Feature Engineering

**What I needed help with:**

After developing the original model, I wanted to see whether additional features would improve its predictions.

**AI assistance received:**

I used ChatGPT to explore additional features based on shot distance, defensive pressure, player speed, and shot clock time.

**How I used ChatGPT:**

I tested five additional features and compared their performance with the original model. None of them improved the results, which showed me that adding more features does not always lead to better predictions.

*Prompts from this stage are still being retrieved from my conversation history.*

---

## 4. Evaluating and Improving the Model

**What I needed help with:**

I needed to understand how well my model was performing and whether changing its settings would improve the results.

**AI assistance received:**

ChatGPT helped me understand accuracy, ROC AUC, and log loss, and guided me in comparing the original Gradient Boosting model with a tuned version.

**How I used ChatGPT:**

I compared both models using the same validation data. The tuned model had slightly higher accuracy, but the original model performed slightly better on ROC AUC and log loss.

I selected the original model because log loss is the most important metric for evaluating predicted probabilities.

*Prompts from this stage are still being retrieved from my conversation history.*

---

## 5. Organizing My Google Colab Notebook

**What I needed help with:**

Once the model was finished, I wanted my notebook to look professional and be easy for others to understand.

**Prompts I used:**

- "the nba shot prediction using machine learning break it down event more make"
- "make it slightly shorter and make it look simple"
- "make it simple add a little explanation and make it look professional"
- "add more information about the project explain it in depth"
- "okay now what do i do next"
- "am i supposed to add explanations nextx to each code is this a requiment"
- "help me do what we were trying to do before add prompts to every single peice of code in the colab"

**How I used ChatGPT:**

ChatGPT helped me write an introduction for the project and add short explanations above my code cells. This made the notebook easier to follow without changing the purpose of the project.

---

## 6. Preparing the Final Predictions

**What I needed help with:**

I needed to make sure my prediction file followed the correct submission format.

**Prompts I used:**

- "okay is there anyhting else i need to do or am i done"
- "okay help me do this then"
- "okay since weve done almost everything help me do that last part"

**How I used ChatGPT:**

ChatGPT helped me review the submission requirements and identify an issue with the prediction column name.

I used the Google Colab terminal to rename the column from `outcome` to `make_prob` and confirmed that the file contained all 213,977 predictions.

---

## 7. Preparing the GitHub Submission

**What I needed help with:**

I wanted to submit my project directly from Google Colab instead of uploading each file manually.

**Prompts I used:**

- "okay now that i have done that how do i submit the file"
- "am i able to submit it through the google colab terminal if so can you help me do thta"
- "first of all how do i access the terminal in google collab"

**How I used ChatGPT:**

ChatGPT guided me through opening the Colab terminal, checking which files were available, and preparing the project files for GitHub.

---

## 8. Writing the Project Report

**What I needed help with:**

I wanted to create a professional report explaining the project, the models I developed, and the results.

**Prompts I used:**

- "help me construct the project write up where should i construct it to make it the best it could possibly be"
- "help me construct this"

**How I used ChatGPT:**

ChatGPT helped me organize the report into sections covering the dataset, model development, feature engineering, evaluation, limitations, and conclusions. I also used Claude to format the final report and create a Google Doc version.

All results in the report come from my Colab notebook, including why I selected the original Gradient Boosting model.

---

## 9. Documenting AI Assistance

**What I needed help with:**

I needed to create an `ai_prompts.md` file explaining how I used AI during the project.

**Prompts I used:**

- "how do i do the ai prompts.md"
- "help me structure the ai prompts.md try to make it seem"
- "for understanding the dataset use the prompts i used when attempting to understand the dataset"
- "generate the prompts for everything"

**How I used ChatGPT:**

ChatGPT and Claude helped me organize my AI usage into clear sections. I only included prompts I could verify and noted the stages where prompts still need to be added.

---

## Final Reflection

Overall, AI was a helpful resource throughout this project. I used it to understand machine learning concepts, troubleshoot problems, interpret model results, and organize my final submission.

One of the most useful parts was being able to ask follow-up questions when I didn't understand something. This helped me work through the project step by step.

I used Google Colab to run all code, evaluate the model's performance, and generate the final predictions.
