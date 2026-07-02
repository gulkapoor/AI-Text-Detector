#  AI Text Detector

A web application built with **Flask** and **Hugging Face Transformers** that analyzes text and predicts whether it is **AI-generated** or **Human-written**.

---

##  Features

- Detects AI-generated vs Human-written text
- Confidence scores for each prediction
- Interactive and responsive web interface
- Real-time text analysis
- Clean and modern UI

---

##  Tech Stack

### Backend
- Python
- Flask
- Hugging Face Transformers

### Frontend
- HTML
- CSS
- JavaScript

### Machine Learning
- Zero-Shot Classification
- `facebook/bart-large-mnli`

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/gulkapoor/AI-Text-Detector.git
```

Move into the project folder:

```bash
cd AI-Text-Detector
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

##  Model Used

This project uses the Hugging Face **Zero-Shot Classification** pipeline with:

- `facebook/bart-large-mnli`

The model compares the input text against the labels **"AI-generated"** and **"Human-written"** to provide a confidence score for each category.


## 👩‍💻 Author

**Gul Kapoor**

- GitHub: https://github.com/gulkapoor
