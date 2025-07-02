# 🎵 Music Recommendation System

This project is a **machine learning-based music recommendation system** built with **Python**, **Streamlit**, and **Spotify API**. It recommends similar songs based on user input using **TF-IDF vectorization** and **cosine similarity**.

---

## 🚀 Features

- Recommends top 20 similar songs based on lyrics/text data
- Displays **album cover** using Spotify API
- Interactive UI with **Streamlit**
- Large data handling using **Git LFS**

---

## 📁 Project Structure

├── .gitattributes # Git LFS tracking for large files
├── df.pkl # Pickled DataFrame containing song data
├── similarity.pkl # Precomputed similarity matrix (Large file)
├── main.py # Streamlit app main file
├── requirements.txt # List of required Python packages
├── README.md # Project overview



---

## 🧠 How it Works

1. Song lyrics are cleaned and tokenized using NLTK.
2. `TfidfVectorizer` converts text into numerical features.
3. `cosine_similarity` calculates similarity between songs.
4. Spotify API fetches the album cover of the recommended songs.
5. Streamlit provides a user interface to interact with the model.

---

## 🔧 Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/Kishorekannann82/Music_Recommendation_System.git
cd Music_Recommendation_System
pip install -r requirements.txt



🧑‍💻 Author
Kishore Kannan
