# 🧠 Fine-tuning DistilBERT for Sentiment Analysis (IMDB Dataset)

This project demonstrates fine-tuning of a pre-trained Transformer model (**DistilBERT**) on the **IMDB movie reviews dataset** for binary sentiment classification (positive/negative).

The goal was to build a lightweight NLP model capable of understanding the emotional tone of text using a relatively small dataset and limited compute resources (Google Colab GPU).

---

## 🚀 Project Overview

- **Model:** DistilBERT (`distilbert-base-uncased`)  
- **Task:** Sentiment Analysis (Binary classification)  
- **Dataset:** IMDB (50,000 movie reviews)  
- **Frameworks:** Hugging Face Transformers, Datasets, PyTorch  
- **Environment:** Google Colab (with GPU acceleration)

---

## 📊 Results

| Metric | Value |
|---------|--------|
| Accuracy | **91.1%** |
| Loss | 0.238 |
| Epochs | 6 |
| Eval samples/sec | 65 |

The model correctly classified:
- *"This movie was amazing, I loved every minute!"* → ✅ **Positive**  
- *"It was the worst film I have ever seen."* → ✅ **Negative**

---

## 🧩 Key Learnings

- Practical understanding of **tokenization**, **model fine-tuning**, and **evaluation metrics**  
- How model weights adapt during supervised fine-tuning  
- Importance of GPU optimization and dataset preprocessing  
- Early exploration into how LLMs encode and interpret sentiment

---

## ⚙️ How to Run

You can open and run this notebook directly in **Google Colab**:

🔗 [Open in Colab](https://colab.research.google.com/drive/your_colab_id_here)

Make sure to:
1. Install required dependencies (`transformers`, `datasets`, `torch`)  
2. Enable GPU runtime  
3. Run cells sequentially

---

## 📚 Future Work

- Experiment with larger models (BERT-base, RoBERTa)  
- Analyze attention weights for interpretability  
- Extend to multi-class emotion classification  

---

## 🧾 Author

**Mgr. Tomáš Vodáček**  
Transitioning from business and systems management into AI research.  
Exploring the intersection of **machine learning, psychology, and complex adaptive systems**.

---

⭐ *If you find this project useful or inspiring, feel free to star it or connect with me on [LinkedIn](https://www.linkedin.com/in/tomáš-vodáček-79b85328a).*
