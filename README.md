# Simple-RNN: IMDB Movie Review Sentiment Analysis

This project is an end-to-end demonstration of movie review sentiment analysis using a Simple RNN (Recurrent Neural Network) in TensorFlow/Keras. The app analyzes reviews from the IMDB dataset and predicts whether the sentiment is positive or negative.

## Features

- Train and evaluate a Simple RNN model on the IMDB dataset.
- Use Keras and TensorFlow for deep learning.
- Visualize word embeddings.
- Streamlit web app for interactive predictions.
- Automatically scores known positive/negative words.

## Files

- `simplernn.ipynb`: Notebook for training the RNN model on the IMDB dataset.
- `main.py`: Streamlit app for real-time sentiment prediction.
- `prediction.ipynb`: Notebook for loading the trained model and making single predictions.
- `embedding.ipynb`: Demonstrates word embedding concepts.
- `requirements.txt`: Python dependencies.
- `LICENSE`: Open-source license.
- `README.md`: This file.

## How to Run

1. Clone the repository:
    ```
    git clone https://github.com/DeepakAthreshR/simple-rnn.git
    cd simple-rnn-imdb
    ```

2. (Optional) Create a virtual environment:
    ```
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
    ```

3. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

4. To train the model, open `simplernn.ipynb` and run all cells.

5. To launch the web app:
    ```
    streamlit run main.py
    ```

## Acknowledgements

- IMDB Dataset from Keras
- TensorFlow and Streamlit teams

---

## 3. How to Upload and Version Code on GitHub

### Initialize and stage your project with Git

git init
git add .
git commit -m "Initial commit: Simple RNN IMDB Sentiment Analysis"

### Create your GitHub Repository

1. Go to [GitHub](https://github.com/) and sign in.
2. Click the “+” at the top right and “New repository.”
3. Give it a name (e.g., `simple-rnn-imdb`), add a description, and choose public/private.
4. (Don’t initialize with README, since you have your own.)

### Push your local project to GitHub

git remote add origin https://github.com/DeepakAthreshR/simple-rnn.git
git branch -M main
git push -u origin main

---

### 4. Recommendations for New GitHub Users

- **.gitignore**: Add a `.gitignore` file to avoid uploading large datasets, virtual env folders (like `/venv`), and model files you never want to share (to create: `python .gitignore` and add things like `venv/`, `.ipynb_checkpoints/`, etc).
- **README.md**: This is the most important file for describing and showcasing your project.
- **LICENSE**: Always include an open-source license.
- **Commit Regularly**: Each time you make major changes, use `git add .`, then `git commit -m "message"`, then push.
- **Screenshots** (optional): Include images (in a `/screenshots/` folder or in your README) to show your app in action!

---

### 5. Example .gitignore for Python projects

Add the following as `.gitignore`:

venv/
pycache/
*.pyc
.DS_Store
.ipynb_checkpoints/
simple_rnn_imdb.h5


