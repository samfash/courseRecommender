Course Recommender System

This project is a course recommender system that helps users find the best courses based on their interests and previous learning experiences.
By leveraging user profiles and course metadata, the system provides personalized course suggestions, making it easier for learners to find relevant content across various platforms like Coursera, edX, and Udemy.

**Features**
- **Personalized course recommendations**
- **Integration with various course platforms**
- **Interactive user interface for exploring recommendations**

**Technologies used**
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, TensorFlow, Flask
- **Visualization:** Matplotlib, Seaborn
- **Database:** PostgreSQL

``` bash
git clone https://github.com/samfash/courseRecommender.git
cd course-recommender
pip install -r requirements.txt
```
```
pip install -r requirements.txt
```

```
python app.py
```

Data sourced from Coursera and edX.

Preprocessing:
- Data Cleaning: Removal of duplicate entries, handling of missing values.
- Feature Engineering: Extraction of relevant features like course difficulty, duration, and topic.
- Normalization: Normalized course ratings to ensure consistency across platforms.

Modelling and evaluation
- Collaborative Filtering: Utilizes user ratings and interactions to recommend courses that similar users have liked.
- Content-Based Filtering: Recommends courses based on the content similarity between previously taken courses and available courses.

Precision and Recall: Evaluated the relevance of the recommendations.


**Results**
- The Course Recommender System effectively provided personalized recommendations with an RMSE of 0.85 and a precision of 92%. The system demonstrated significant improvement in user satisfaction compared to traditional search-based methods.

**Contributions**
- Fork the repository.
- Create a new branch: git checkout -b feature-branch-name.
- Commit your changes: git commit -m 'Add some feature'.
- Push to the branch: git push origin feature-branch-name.
- Submit a pull request.