# XAI-501-Project


I. Project title
**Enhancing Language Model-Driven Code Generation through the PAD Paradigm**

II. Project introduction
Objective: To address the existing gap in systematic integration of instruction following, code execution, and subsequent debugging in language models. Our project aims to harness the power of the CodeLlama open-source model and enhance it using a specialized dataset derived from GPT-4.

Motivation: The increasing prominence of language models in code generation has garnered significant interest. Despite the advancements, there is a palpable need to ensure that language models not only generate code but also effectively follow instructions, execute the generated code, and perform debugging. The project seeks to demonstrate the value of a targeted approach, using the PAD (Plan, Act, and Debug) paradigm, in improving the performance of language models in autonomous tasks.

III. Dataset description
Our dataset is a curated subset from GPT-4, specifically tailored to support the "PAD: Plan (generation), Act (Execution), and Debug (Re-generation)" paradigm.

**Splitting the Dataset:**

- **Training Dataset**: This subset is the most extensive portion of our dataset, containing input data (coding scenarios, problems, and requirements) along with the correct output (desired code generation). 

- **Validation Dataset**: This subset contains a smaller segment of the data, both input and the corresponding ground truth. It is designed for participants to tune and refine their models, ensuring optimal performance when subjected to unseen data.

- **Test Dataset**: HumanEval, MBPP, DS1000 like coding task ConvFin like Financial Benchmark.

For project participants, both training and validation datasets will be provided, encompassing the necessary input data alongside the correct output (ground truth). This ensures that participants have the resources to not only learn but also validate the performance of their models.
