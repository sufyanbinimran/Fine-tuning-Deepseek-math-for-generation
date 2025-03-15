# Fine-Tuning Deepseek-Math for Math Riddle Generation & Meme Repair

## Overview
This project fine-tunes **Deepseek-Math** to tackle two interesting problems:
1. **Math Riddle Factory** – Generating creative math riddles with correct solutions.
2. **Math Meme Repair** – Correcting viral math memes with proper explanations.

## Features
- Fine-tunes Deepseek-Math on a **custom dataset** of math riddles and incorrect memes.
- Generates **original math riddles** with solutions.
- Detects and **fixes incorrect math memes**, providing accurate explanations.
- Trained using **Hugging Face Transformers** and **PyTorch**.

## Dataset
- **Math Riddle Factory**: 30 handcrafted math riddles with solutions.
- **Math Meme Repair**: 20 incorrect viral math problems with corrected solutions.

## Fine-Tuning Approach
1. **Data Preparation** – Format riddles and memes for supervised fine-tuning.
2. **Model Training** – Fine-tune **Deepseek-Math** on our dataset.
3. **Evaluation** – Generate new riddles and correct meme errors.

## Results
- **Generated Riddles:** The model successfully created unique math riddles.
- **Meme Fixing:** It correctly identified and explained math errors in viral memes.

## Example Outputs
### 1. Math Riddle Generation
**Generated Riddle:** *What number becomes zero when you subtract 15 from half of it?*  
**Answer:** 30  

### 2. Math Meme Repair
**Wrong Meme:** `8 ÷ 2(2+2) = 1`  
**Correct Answer:** `16` (Following PEMDAS)

## Installation & Usage
### Install Dependencies
```bash
pip install transformers torch datasets
```
### Run Fine-Tuning
```python
python fine_tune.py
```
### Test the Model
```python
test_model.py
```

## Blog Post
📝 **Read More:** [Fine-Tuning GPT for Math Riddles & Meme Repair](https://medium.com/@sufyanbinimran/fine-tuning-gpt-for-math-riddles-meme-repair-a-fun-ai-experiment-af412794013a)
