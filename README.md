# XAI-501-Project


I. Project title
**Enhancing Language Model-Driven Code Generation through the PAD Paradigm**

II. Project introduction
Objective: To address the existing gap in systematic integration of instruction following, code execution, and subsequent debugging in language models. Our project aims to harness the power of the CodeLlama open-source model and enhance it using a specialized dataset derived from GPT-4.

Motivation: The increasing prominence of language models in code generation has garnered significant interest. Despite the advancements, there is a palpable need to ensure that language models not only generate code but also effectively follow instructions, execute the generated code, and perform debugging. The project seeks to demonstrate the value of a targeted approach, using the PAD (Plan, Act, and Debug) paradigm, in improving the performance of language models in autonomous tasks.

III. Dataset description
Our dataset is a curated subset from GPT-4, specifically tailored to support the "PAD: Plan (generation), Act (Execution), and Debug (Re-generation)" paradigm.
One data contains input data (coding scenarios, problems, and requirements) along with the correct output (desired code generation). 
I collected almost 1K dataset with (using OPENAI API GPT4 costs $200)

**Splitting the Dataset:**

- **Training Dataset**: 80% of 1K
- **Validation Dataset**: 10% of 1K
- **Test Dataset**: 10% of 1K

For project participants, both training and validation datasets will be provided, encompassing the necessary input data alongside the correct output (ground truth). This ensures that participants have the resources to not only learn but also validate the performance of their models.


## Contact

2022021568@korea.ac.kr
