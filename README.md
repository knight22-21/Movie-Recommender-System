# Movie-Recommender-System

An end-to-end project for a content-based movie recommendation system.

## Project Report: Content-Based Movie Recommender System

### 1. Introduction

This project focuses on designing a content-based movie recommendation system that suggests five similar movies based on user input. The system leverages text vectorization techniques, specifically Bag of Words, and utilizes the TMDB 5000 Movie Dataset from Kaggle to train the recommendation model.

### 2. Objectives

1. **Develop a Movie Recommender:** Build a recommendation engine that suggests similar movies based on user input using content-based filtering.
2. **Utilize Text Vectorization:** Implement Bag of Words to convert movie descriptions into a numerical format suitable for analysis.
3. **Evaluate Model Performance:** Assess the recommendation system's effectiveness and accuracy.

### 3. Methodology

#### 3.1 Data Collection

The TMDB 5000 Movie Dataset was used for this project, which includes detailed information about various movies, such as titles, genres, and descriptions. This dataset serves as the foundation for training the recommendation model.

#### 3.2 Data Preprocessing

1. **Data Cleaning:**
   - Removed unnecessary columns and missing values.
   - Standardized the format of movie titles and descriptions.
  
2. **Text Vectorization:**
   - **Bag of Words:** Transformed movie descriptions into a Bag of Words representation to create a numerical feature set.


#### 3.3 Model Development

The recommendation system was developed using the following steps:

1. **Model Selection:** A content-based filtering approach was chosen to recommend movies similar to those that users input.
2. **Training:** The model was trained on the processed dataset to establish a correlation between movie descriptions and their similarities.
3. **Recommendation Generation:** Implemented a mechanism to suggest five movies based on the similarity scores calculated from the Bag of Words representation.


### 4. Results

The deployed movie recommender system successfully generated relevant movie suggestions based on user input. Users reported satisfaction with the accuracy and relevance of the recommendations provided by the system.

### 5. Conclusion

The project successfully developed a content-based movie recommendation system. The use of Bag of Words for text vectorization proved effective in generating similar movie recommendations. This system demonstrates the practical application of machine learning in enhancing user experiences in the film industry and sets a foundation for future improvements, such as integrating collaborative filtering techniques.

### 6. References

- TMDB 5000 Movie Dataset: [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Scikit-learn Documentation: [Scikit-learn](https://scikit-learn.org/)


---
