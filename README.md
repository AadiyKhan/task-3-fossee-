# Python Screening Task 3: Evaluating Open Source Models for Student Competence Analysis

## Project Overview

This repository contains a research plan and evaluation for identifying open source AI models suitable for analyzing student competence in Python programming. The goal is to explore models that can generate meaningful prompts, assess conceptual understanding, and identify learning gaps without directly providing solutions.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Git
- Internet connection for downloading models

### Installation
1. Clone this repository:
   ```bash
   git clone [repository-url]
   cd task-3(fossee)
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. For model evaluation, you may need additional setup:
   - **StarCoder**: Available through Hugging Face Transformers
   - **CodeBERT**: Available through Hugging Face Hub
   - **CodeT5**: Available through Hugging Face Hub

## Repository Structure

```
task-3(fossee)/
├── README.md                 # This file
├── research_plan.md         # Detailed research plan
├── model_evaluation.md      # Model evaluation results
├── requirements.txt         # Python dependencies
└── example_code/           # Sample student code for testing
    ├── basic_functions.py
    ├── loops_and_conditions.py
    └── misconception_examples.py
```

## Research Approach

Our evaluation focuses on three key aspects:
1. **Code Analysis Capabilities** - How well models understand Python syntax and semantics
2. **Educational Prompt Generation** - Ability to create questions that assess understanding
3. **Misconception Detection** - Identifying common programming errors and gaps

## Key Findings

- **StarCoder** shows strong potential for code understanding but requires significant computational resources
- **CodeBERT** offers a good balance between performance and efficiency for educational use
- **Lightweight alternatives** like fine-tuned smaller models may be more practical for real-world deployment

