# Ulises: Explainable AI for the Legal Sector

Welcome to the repository for the "Ulises" system, a research project advancing Explainable Artificial Intelligence (XAI) in the legal domain. This repository contains all the necessary resources to reproduce the experiments and validate the findings presented in our accompanying paper.

---

## Abstract

This research contributes to the field of Explainable Artificial Intelligence (XAI) applied to the legal sector. A comprehensive literature review revealed a predominance of quantitative approaches to explainability, highlighting a gap in methods applicable to disciplines such as Law, where numerical methods face limitations. To address this need, we implemented and validated alternative non-quantitative approaches, such as Chain of Thought and Retrieval-Augmented Generation. These methods proved effective in enhancing the transparency of AI reasoning, enabling better tracking of information processing and response generation through formats accessible in commercial software.

A key aspect of this work is the comparison of our system, named "Ulises," with advanced models like Anthropic's Claude Opus and OpenAI's o1-preview. Although the comparison focused exclusively on accuracy, it is important to note that the primary goal of our system was to achieve greater explainability, not necessarily higher accuracy. Nonetheless, "Ulises" not only met its explainability objectives but also achieved improved accuracy compared to the analyzed models. These results emphasize the importance of integrating relevant external information and designing specific prompts as key factors for optimizing models with lower computational capacity. Both the results of our experiments and the developed code are openly accessible, promoting transparency and collaborative development.

---

## Repository Contents

This repository contains the following components:

### 1. **Synthetic Case Generator**
- Code for generating synthetic legal cases for testing purposes.
- Includes configurable parameters to customize case generation for various scenarios.

### 2. **Ulises Code**
- Implementation of the "Ulises" system with python 3.12.7
- Contains modules based on the IRAC framework.

### 3. **Requirements.txt**
- Lists all the Python dependencies required to run the project.
- Ensures a smooth setup and execution of the code.

### 4. **Relevant Data**
- All the data can be found at the following link: [Google Drive Link](https://drive.google.com/drive/folders/1bPJvQ7lr1aGZxkqZVyLitK-AOTHqlqZC?usp=drive_link).

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Authors
Main Author: Piero Alexis Malca Vilchez.
Contributors: Enzo Rodrigo Gomez Rojas and Cesar Humberto Quiñones Costa.

---

## Contact
For questions or collaborations, please contact:
- Piero Alexis Malca Vilchez: pa.malcav@gmail.com
