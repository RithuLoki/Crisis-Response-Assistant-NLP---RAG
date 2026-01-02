# Crisis Response Assistant using NLP & RAG (Non-Clinical)

## Project Description
This project presents a **Crisis Response Assistant** built using **Natural Language Processing (NLP)** and **Retrieval-Augmented Generation (RAG)** techniques.  
The system is designed strictly as a **non-clinical, non-diagnostic, and non-therapeutic educational tool**.

The assistant analyzes short user inputs describing concerns such as academic stress, financial worries, work stress, or general anxiety, and provides **supportive, informational responses** grounded in a curated knowledge base.  
At every stage, the project follows **responsible AI principles**, prioritizing user safety, transparency, and ethical boundaries.

---

## Problem Statement
In many situations, individuals seek immediate guidance during stressful or uncertain moments. While AI systems can help provide general information, it is critical that such systems **do not replace professional medical or psychological support**.

This project explores how NLP and RAG can be used to build a **safe and explainable crisis-support assistant** that:
- Offers educational insights
- Avoids clinical advice
- Encourages professional help when required

---

## Key Features
- Rule-based input categorization into non-diagnostic themes
- Retrieval-Augmented Generation (RAG) using sentence embeddings
- Curated knowledge base with educational content
- Safety and fallback logic for high-risk or low-confidence queries
- Explainable responses with source category and title
- End-to-end pipeline demonstration
- Simple interactive text-based interface

---

## System Workflow
1. User provides a short text describing their concern
2. Input is categorized into predefined non-clinical themes
3. Relevant knowledge base entries are retrieved using semantic similarity
4. Safety checks are applied for high-risk language
5. An educational and grounded response is generated
6. Source information is shown for transparency

---

## Technologies Used
- Python
- Sentence Transformers
- Scikit-learn
- NumPy
- Jupyter Notebook / Google Colab

---

## How to Run the Project
1. Clone or download this repository
2. Open the notebook in **Google Colab** or **Jupyter Notebook**
3. Run all cells sequentially from top to bottom
4. Use the interactive interface at the end of the notebook to test sample queries

---

## Ethical Disclaimer
This project is intended **only for educational and research purposes**.

- It does **not** provide medical, psychological, or therapeutic advice
- It does **not** diagnose or treat any condition
- It is **not a replacement** for professional help

If a user is experiencing a serious crisis or feels unsafe, they should immediately contact qualified professionals or emergency services.

---

## Limitations
- Input categorization is rule-based and may not capture all linguistic variations
- Safety detection relies on keyword matching and may require further expansion
- Knowledge base is limited to predefined educational content

---

## Future Scope
- Improve categorization using supervised or transformer-based models
- Enhance high-risk detection with contextual NLP methods
- Expand the knowledge base with verified public resources
- Add multilingual support
- Develop a web-based interface with controlled deployment safeguards

---

## Author
**Rithikaa V**  
B.Tech – Information Technology  
