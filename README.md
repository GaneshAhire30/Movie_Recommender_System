# Movie_Recommender_System
![image](https://github.com/user-attachments/assets/4dd02992-56a6-4d29-b0f8-a3a36f7dd567)

## AI PROJECT ON MOVIE RECOMMENDATION

### BUSINESS CASE:
The objective of this project is to develop a movie recommender system that provides personalized movie recommendations to users based on their preferences and previous interactions.

### TASK: COLLABORATIVE FILTERING AND CONTENT-BASED RECOMMENDATION
This project is divided into multiple steps:

- Importing Libraries
- Data Preprocessing [Preparing Datasets]
- Building Recommendation Model
- Model Evaluation
- Recommendations for Users
- Model Testing
- Deployment using Streamlit

---

## DATA SUMMARY

- The dataset consists of movie ratings and metadata such as movie title, genre, and release year.
- It includes information such as user ratings, movie genres, and movie descriptions.

---

## LOADING DATA / PREPARING DATA

- The dataset for this project is loaded and prepared using libraries like **Pandas** for data manipulation and **NumPy** for numerical operations.
- The data is preprocessed to handle missing values, normalize ratings, and prepare it for model building.
- **Collaborative filtering** and **content-based filtering** are used to build the recommendation system.
- For collaborative filtering, user-item interaction matrices are created to identify patterns in user preferences.
- For content-based filtering, movie metadata (genres, descriptions) are used to make recommendations based on movie similarity.

---

## DATA PROCESSING

- The dataset is loaded, cleaned, and preprocessed using **Pandas**. Missing values are handled, and categorical variables are encoded where necessary.
- Feature engineering is applied to extract relevant features such as genre, keywords, or movie metadata for better recommendations.

---

## BUILDING RECOMMENDATION MODEL

- The **Collaborative Filtering** model is implemented using **Matrix Factorization** techniques such as **SVD (Singular Value Decomposition)**.
- The **Content-Based Filtering** model is built using movie metadata, creating a similarity matrix based on genre, plot keywords, and other available features.
- Hybrid recommendation systems can also be explored by combining collaborative and content-based filtering.

---

## RECOMMENDATIONS FOR USERS

- After training the model, recommendations are generated for a given user based on their ratings or preferences.
- Top recommended movies are suggested to the user based on their previous interactions or the movie metadata they are most interested in.

---

## TESTING THE MODEL

- The model is tested by evaluating the recommendation quality and comparing it to actual user ratings.
- **Example Testing Output:**
  - **recommend("Avatar")**: Top 5 recommended movies:
    1. Aliens vs Predator: Requiem
    2. Aliens
    3. Falcon Rising
    4. Independence Day
    5. Titan A.E.

---

## DEPLOYMENT USING STREAMLIT

- The trained recommender system is deployed as a simple web app using **Streamlit**.
- Users can enter their preferences, and the system will provide movie recommendations in real-time.
- **Steps to deploy:**
  1. Install **Streamlit** by running:
     ```bash
     pip install streamlit
     ```
  2. Create a `streamlit_app.py` file and set up the UI for user interaction.
  3. Use the trained model to generate recommendations.
  4. Run the Streamlit app:
     ```bash
     streamlit run streamlit_app.py
     ```

---

## CONCLUSION

- This movie recommender system demonstrates the power of machine learning in providing personalized recommendations.
- The system achieves high accuracy in recommending movies based on user preferences, using collaborative and content-based filtering techniques.

---

## LIBRARIES USED

- Pandas
- NumPy
- Scikit-learn
- Surprise (for Collaborative Filtering)
- Matplotlib (for visualization)
- Streamlit (for Deployment)
- NLTK (for text processing, if applicable)

---

## TOOL USED

- Jupyter Notebook
- PyCharm
