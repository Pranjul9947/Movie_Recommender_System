
# 🎬 Movie Recommender System  

This is a content-based movie recommender system that suggests movies based on cosine similarity between vectorized movie features. The system utilizes the **TMDB dataset** to provide relevant recommendations.  

## 📌 Features  
✅ Recommends movies based on content similarity  
✅ Uses **cosine similarity** for recommendation  
✅ Processes and vectorizes movie metadata  
✅ Simple and efficient implementation  

## 🛠️ Technologies Used  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TMDB dataset  

## 📂 Dataset  
The recommender system is built using the **TMDB dataset**, which contains movie metadata, including:  
- Title  
- Overview  
- Genre  
- Cast & Crew  
- Keywords  

## 🔢 Approach  
1. **Data Preprocessing**:  
   - Extracted relevant features (title, genres, keywords, cast, etc.)  
   - Cleaned and tokenized text-based features  
   - Combined features into a single text representation  
2. **Vectorization**:  
   - Used **TF-IDF (Term Frequency-Inverse Document Frequency)** or **CountVectorizer**  
   - Converted text features into numerical vectors  
3. **Similarity Calculation**:  
   - Computed **cosine similarity** between movie vectors  
   - Found the most similar movies for a given input movie  
4. **Recommendation Generation**:  
   - Retrieved top N most similar movies  

## 🚀 How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/movie-recommender.git  
   cd movie-recommender  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the script:  
   ```bash  
   python recommend.py  
   ```  
4. Enter a movie name to get recommendations!  

## 📌 Example Output  
```
Enter a movie name: Inception  
Recommended Movies:  
1. Interstellar  
2. The Prestige  
3. The Matrix  
4. Memento  
5. Shutter Island  
```

## 📜 License  
This project is open-source and available under the **MIT License**.  

