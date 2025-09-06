# 🦠 COVID-19 Symptoms Prediction #

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**Description**\
A **Python-based Machine Learning project** that predicts whether a person is **COVID Positive or Negative** based on their symptoms.  
The project uses two ML models — **Logistic Regression** and **Random Forest** — and compares their performance with accuracy, precision, recall, and F1-score.  
It is lightweight and runs in the terminal or Google Colab environment.

---

## Table of Contents

- [Live Demo](#live-demo)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Requirements](#requirements)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Contributing](#contributing)
- [License](#license)

---

## Live Demo

[Click here to try on Google Colab](https://colab.research.google.com/drive/19cHk3g4pZnjPGbtVKKqAaVRpX-QIGgYi?usp=sharing) 

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/divya-00/covid19_symptom_predictor.git
   
2. Open the folder in your preferred Python environment (like **Google Colab, Jupyter Notebook, or IDLE**).

## How to Use

1. Run the script in a Python environment:

```bash
python covid_prediction.py
```
2. The program will:

- Ask you a series of **Yes/No questions** about symptoms.  
- Convert your answers into numeric values (`1` for Yes, `0` for No).  
- Use the trained ML model to predict **COVID Positive / COVID Negative**.  
- Display a neat **tabular summary** of your inputs along with the final result.  

### Sample User Input Table



| Symptom       | Your Answer |
|---------------|------------|
| Fever         | Yes        |
| Dry Cough     | No         |
| Sore throat   | Yes        |
| Running Nose  | No         |
| Fatigue       | Yes        |

**✅ COVID Negative**


## Requirements

Python 3.x with the following libraries:

- pandas  
- scikit-learn  
- tabulate  
- kagglehub  

Install all dependencies with:

```bash
pip install -r requirements.txt
```
## Features

- Symptom-based **COVID-19 prediction**  
- Encodes Yes/No inputs → numerical values  
- Comparison of **Logistic Regression vs Random Forest**  
- Outputs metrics (Accuracy, Precision, Recall, F1 Score) in a neat table  
- Easy-to-run Python script for beginners and learners  

---

## Tech Stack

- **Language:** Python 3.x  
- **Libraries:** scikit-learn, pandas, tabulate, kagglehub  

**Future Upgrades:**

- Add GUI (Tkinter or Streamlit)  
- Deploy as a Web App  
- Include probability/confidence scores in predictions  

---

## Contributing

Want to improve this project? 🎯

1. Fork the repo  
2. Create a new branch (`feature-new`)  
3. Commit your changes  
4. Submit a pull request  

---

## License

This project is licensed under the terms of the [MIT license](LICENSE).  
Copyright © rights are reserved, made with :heart: DeviDivyaSri Perni.

