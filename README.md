# Sagacity: A Mental Health Support Platform

A digital platform for accessible, anonymous mental health support. A BERT-based NLP model runs behind a Flask backend and powers a React chatbot interface. The work is described in a co-authored, published research paper.

## Highlights

- BERT-based NLP model with an **F1-score of 0.86**
- Model served through a **Flask** backend to a **React** chat frontend
- Co-authored research paper *Mental Health Support Platform*, published in IJRAR (May 2024)
- Built as an academic project, Sep 2023 to Jan 2024

## Tech stack

Python, BERT (Transformers), NLP, Flask, React

## Overview

Sagacity aims to make mental health support easier to reach. It offers anonymous access, real-time chatbot support, and a resource hub, with tools for institutions and for prevention and education.

## Features

**For users**
- Anonymous access to support in a safe, confidential space
- Real-time interactive support through a chatbot
- A hub of articles, self-help tools and resources

**For institutions**
- Administrative dashboard for managing facilities
- Analytics on engagement and platform usage
- Integration with existing healthcare systems

**Prevention and education**
- Alerts that flag early signs of concern
- Educational modules on mental health topics

## Repository structure

| Folder | Contents |
| ------ | -------- |
| `chatbotFrontend/` | React chat interface |
| `dataset/` | Data used to train and evaluate the model |
| `proh/` | Flask backend (`main.py`), HTML templates and static files, trained chatbot model and embeddings (`model.h5`, `*.dump`, `*.pkl`), and the training notebooks (`chatbot.ipynb`, `TOC_QNA_CHATBOT (1).ipynb`) |

## Getting started

**Prerequisites:** Python 3.9+, Node.js 18+

**Backend**

```bash
git clone https://github.com/Nishtha-Tiku/Sagacity-A-HealthBot.git
cd Sagacity-A-HealthBot/proh
pip install -r requirements.txt
python main.py
```

**Frontend**

```bash
cd chatbotFrontend
npm install
npm start
```

The backend prints a local address in the terminal (Flask default is `http://127.0.0.1:5000`). Open it in your browser.

## Results

| Metric | Value |
| ------ | ----- |
| F1-score | 0.86 |

## Publication

*Mental Health Support Platform*, International Journal of Research and Analytical Reviews (IJRAR), published May 2024 (Paper ID: IJRARTH00219).

Published Paper : https://drive.google.com/file/d/1ezjl3xHk-9R-VWVajx5WKdbGRMtmoXMj/view?usp=sharing

## Disclaimer

Sagacity is an academic project. It is not a substitute for professional mental health care. If you are in crisis, contact your local emergency number or a helpline in your country.
