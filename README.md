# StyleSnitch

**AI-Powered Art Style Profiler & Recommender**  
Discover your unique visual fingerprint using deep learning embeddings and style similarity analysis.

![screenshot-placeholder](docs/screenshot.png)

## Demo

Coming Soon!

## Overview

**StyleSnitch** is a personalized AI tool that analyzes the "style DNA" of a user's artwork using computer vision models like CLIP. Upload a few images that define your visual aesthetic, and StyleSnitch will:
- Extract style embeddings using CLIP
- Visualize your style cluster
- Compare new images to your signature look
- Recommend prompts or inspiration based on your style

Built for artists, designers, and digital creators who want insight into their evolving creative identity.

## Features

- Style Signature Extraction using CLIP
- Embedding Visualization (PCA/t-SNE)
- Upload & Compare Image Styles
- Prompt Suggestions based on your visual taste
- Art Style Twin Matching (optional extension)


## Tech Stack

| Layer          | Tools / Libraries                           |
|----------------|----------------------------------------------|
| Backend        | Python, FastAPI or Flask, CLIP, NumPy        |
| Frontend       | React (Vite), Tailwind CSS, Chart.js         |
| AI Models      | OpenAI CLIP, t-SNE, PCA (scikit-learn)       |
| Data Storage   | Local or MongoDB                             |
| Deployment     | HuggingFace Spaces, Render, or Streamlit     |


## Folder Structure

StyleSnitch/
├── backend/
│ ├── app.py
│ ├── model_utils.py
│ └── embeddings/
├── frontend/
│ ├── src/
│ └── public/
├── docs/
│ └── screenshots, diagrams, etc.
├── tests/
│ └── backend_tests.py
├── README.md
└── requirements.txt


## Getting Started

1. **Clone the Repo**
```bash
git clone https://github.com/yourusername/stylesnitch.git
cd stylesnitch
```
2. **Set Up Backend**
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
3. **Run the Frontend**
```bash
cd frontend
npm install
npm run dev
```