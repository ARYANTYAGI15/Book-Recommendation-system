# 📚 Book Recommendation System

A simple and efficient Book Recommendation System built using **cosine similarity** to suggest similar books based on user preferences. The project also includes an interactive **Streamlit** app for easy use and deployment.

---

## 🚀 Features

- Recommends books based on content similarity.
- Utilizes **cosine similarity** on vectorized book features.
- Clean and intuitive **Streamlit UI**.
- Fast and responsive predictions.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- scikit-learn
- Streamlit

---

## 💡 How It Works

1. **Data Preprocessing**:
   - Books metadata is cleaned and structured.
   - Text-based features (e.g., title, author, genre, description) are combined into a single string for vectorization.

2. **Feature Extraction**:
   - TF-IDF or CountVectorizer is applied to convert text to vectors.

3. **Similarity Calculation**:
   - Cosine similarity is used to find similar books based on the vector representation.

4. **User Input**:
   - The user selects a book title via the Streamlit interface.

5. **Recommendation Output**:
   - The app returns the top 5–10 similar books based on cosine similarity scores.

---



---

## 📦 Installation

### Clone the repository
```bash
git clone https://github.com/yourusername/book-recommendation-system.git
cd book-recommendation-system

```
### Installation Requirements
pip install -r requirements.txt

### Streamlit app run
streamlit run app.py

 🙋‍♂️ Author
Aryan Tyagi
9319152999
📫 Contact: aryan.india1515@gmail.com

