# RECOMMENDATION-SYSTEM

*COMPANY* : CODTECH IT SOLUTIONS

*NAME*: NAVANEETH REDDY ADDLA

*INTERN ID* : CT04DF1817

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTHOSH

*DESCRIPTION* :

For this project, I developed a movie recommendation system using collaborative filtering techniques, specifically matrix factorization via Singular Value Decomposition (SVD). The goal was to create a model capable of predicting user preferences for movies they had not yet rated, based on patterns learned from existing user-item rating data. I followed a complete data science pipeline—from dataset acquisition to model evaluation and web app deployment—ensuring the system was both functional and user-friendly.

I began the project by selecting the MovieLens 100k dataset, a widely used benchmark dataset in the recommender systems domain. This dataset contains 100,000 movie ratings provided by 943 users on 1,682 movies. The dataset was chosen due to its balanced size—large enough to capture meaningful user behavior but small enough to process efficiently during development and experimentation.

To work with the data, I used the Surprise library, a Python scikit specifically built for building and evaluating recommender systems. Using Surprise’s built-in dataset loader, I imported the MovieLens 100k dataset and converted it into a format suitable for collaborative filtering. I then split the dataset into a training set (75%) and a testing set (25%) using the library’s train_test_split function to ensure a fair and consistent evaluation process.

The collaborative filtering approach chosen for this project was matrix factorization using SVD (Singular Value Decomposition). SVD is a powerful technique that breaks down the user-item interaction matrix into lower-dimensional representations, uncovering latent factors that explain observed ratings. This method is especially effective in handling sparse rating matrices where most users have rated only a small subset of available items. I trained the SVD model on the training data, allowing it to learn user and item embeddings that capture preferences and characteristics.

Once the model was trained, I evaluated its performance on the test set using two commonly used metrics: Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE). These metrics compare the predicted ratings with actual user ratings to quantify the prediction accuracy. The model achieved an RMSE of approximately 0.9364 and an MAE of about 0.7386, which are solid results for this dataset and approach, indicating that the model is capable of making reasonably accurate predictions.

To demonstrate the practical utility of the recommendation system, I developed a web application using Streamlit, a Python-based framework for building interactive user interfaces with minimal effort. The app allows a user to input a user ID (between 1 and 943), and it then displays the top 5 movie recommendations for that user based on predicted ratings. These recommendations are generated dynamically by the trained SVD model, offering a real-time recommendation experience. The simplicity and responsiveness of the app make it accessible even to users without technical backgrounds.

Throughout the project, I followed best practices in software development and machine learning. I ensured reproducibility by setting random seeds, used modular code for model training and evaluation, and maintained a clear separation between the model logic and the user interface. By the end of the project, I had built a complete recommendation system pipeline—from data loading and model training to evaluation and deployment.

This project not only strengthened my understanding of collaborative filtering and matrix factorization but also gave me hands-on experience in deploying machine learning models for real-world use. The final deliverables include a Jupyter Notebook showcasing the full implementation and evaluation of the recommendation system and a Streamlit app that demonstrates the system’s functionality in an interactive environment. Overall, this end-to-end system highlights the power of collaborative filtering in delivering personalized recommendations and lays the groundwork for more advanced recommender system development in the future.

*OUTPUT* :
