# Research Plan: Evaluating Open Source Models for Student Competence Analysis

## Research Methodology

To evaluate open source AI models for analyzing student competence in Python programming, I will employ a systematic approach that begins with identifying and cataloging relevant models from the current landscape of educational AI tools and code analysis frameworks. My evaluation will focus on three primary categories: large language models fine-tuned for code (such as StarCoder, CodeGen, and CodeT5), specialized code analysis models (like CodeBERT and GraphCodeBERT), and educational-specific tools that have been developed for student assessment. For each candidate model, I will establish comprehensive evaluation criteria including code comprehension accuracy, ability to generate pedagogically sound prompts that assess conceptual understanding rather than syntax memorization, effectiveness in detecting common misconceptions and logical errors, and capacity to provide guided feedback that encourages deeper learning without revealing solutions. The evaluation process will involve creating a standardized test dataset of student-written Python code samples representing various skill levels and common misconception patterns, then systematically testing each model's performance across multiple dimensions including prompt relevance, educational value, and computational efficiency.

The validation phase will involve both quantitative and qualitative assessment methods, comparing model-generated prompts against those created by experienced Python educators and measuring the models' ability to identify predetermined misconceptions in the test code samples. I will specifically evaluate how well each model can distinguish between surface-level syntax errors and deeper conceptual misunderstandings, assess their capacity to generate questions that probe algorithmic thinking and problem-solving strategies, and determine their effectiveness in providing scaffolded guidance that maintains appropriate challenge levels. Based on my preliminary research, I plan to focus detailed evaluation on StarCoder (15.5B parameters, trained on diverse code repositories) as the primary candidate due to its strong performance in code understanding tasks and open-source availability, while also conducting comparative analysis with smaller, more computationally efficient alternatives like CodeBERT to assess the trade-offs between model sophistication and practical deployment considerations. The final assessment will include recommendations for implementation strategies, potential fine-tuning approaches for educational contexts, and identification of scenarios where different models might be most appropriate based on institutional resources and specific pedagogical goals.

## Model Selection Rationale

**Primary Evaluation Target: StarCoder**
- **Strengths**: Extensive training on 35B Python tokens, strong code comprehension capabilities, open-source accessibility
- **Limitations**: High computational requirements (15.5B parameters), may need fine-tuning for educational contexts
- **Evaluation Focus**: Code analysis accuracy, prompt generation quality, misconception detection effectiveness

**Secondary Candidates for Comparison**:
- **CodeBERT**: Smaller footprint, good balance of performance and efficiency
- **CodeT5**: Strong text-to-code and code-to-text capabilities
- **GraphCodeBERT**: Enhanced understanding of code structure through graph representations

## References

1. Li, R., et al. (2023). "StarCoder: may the source be with you!" *arXiv preprint arXiv:2305.06161*
2. Feng, Z., et al. (2020). "CodeBERT: A Pre-Trained Model for Programming and Natural Languages" *arXiv preprint arXiv:2002.08155*
3. Wang, Y., et al. (2021). "CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation" *arXiv preprint arXiv:2109.00859*
