# FAKE-NEWS-DETECTION-APPLICATION
# 📰 Fake News Detection Application

An AI-based **Fake News Detection Application** developed using Python, Natural Language Processing (NLP), Hugging Face Transformers, RoBERTa, and Gradio. The application analyzes a news headline or article and predicts whether the content is likely to be **Real News** or **Fake News**.

## 🚀 Project Overview

The Fake News Detection Application uses a pretrained Transformer-based NLP model to classify news text. Users can enter a headline or news article through an interactive Gradio interface and receive a prediction along with the model's confidence score.

## 🎯 Objectives

* Detect potentially fake or misleading news content.
* Apply Natural Language Processing to news classification.
* Demonstrate the use of pretrained Transformer models.
* Provide an easy-to-use web interface.
* Run the application directly in Google Colab.

## 🛠️ Technologies Used

* **Python**
* **Natural Language Processing (NLP)**
* **Hugging Face Transformers**
* **RoBERTa**
* **PyTorch**
* **Gradio**
* **Google Colab**

## ⚙️ How It Works

1. The user enters a news headline or article.
2. The text is processed by the NLP model.
3. The pretrained RoBERTa model analyzes the text.
4. The model generates a classification result.
5. The application displays the predicted category and confidence score.

## ✨ Features

* 📰 News headline classification
* 🔍 Fake/real prediction
* 🤖 Pretrained Transformer model
* 📊 Confidence score
* 🌐 Interactive Gradio interface
* ☁️ Google Colab support
* ⚡ No model training required

## ▶️ How to Run

1. Open **Google Colab**.
2. Create a new notebook.
3. Copy the complete Python code into one cell.
4. Run the cell.
5. Wait for the pretrained model to download.
6. Open the Gradio link displayed by Colab.
7. Enter a news headline or article.
8. Click **🔍 Detect News**.
9. View the prediction and confidence score.

## 📌 Example

### Input

```text
Scientists have announced a new technology that can produce clean energy
from seawater. Researchers say the technology could help reduce dependence
on traditional energy sources.
```

### Output

```text
✅ REAL NEWS

Confidence: 87.42%

Model Label: REAL
```

## 📂 Project Structure

```text
Fake-News-Detection/
│
├── fake_news_detection.ipynb
└── README.md
```

