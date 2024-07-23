Objective:
To develop a movie recommendation system that enhances user experience by providing personalized movie suggestions based on user preferences 

Goals:

Increase User Engagement: By offering personalized recommendations, users are more likely to spend more time on the platform.
Boost Sales: For platforms that sell or rent movies, personalized recommendations can increase purchase or rental rates.
Improve User Retention: A tailored experience can keep users coming back to the platform, reducing churn rates.
Enhance User Satisfaction: Providing relevant content leads to a more satisfying user experience, resulting in positive reviews and word-of-mouth promotion.

Data Modeling
Data Collection:
  Movie Data: Metadata about movies, including genres, title, cast, crew, keywords

Data Preprocessing:
  Cleaning: Handling missing values, removing duplicates, and normalizing data.
  
  Feature Engineering: Creating useful features from raw data

Data Transformation:
Text Vectorization: Apply word embeddings to movie genres,keywords,cast,crew to create feature vectors.

Modeling Approach:
Cosine Similarity:
Similarity Calculation: Compute the cosine similarity between the text vectors of movies to find similarities between them.
Recommendation Generation: Recommend movies that have high cosine similarity to movies user is looking for.

Streamlit Application Development:
Developed an interactive Streamlit application that allows users to enter a movie name and receive five personalized movie recommendations, integrating movie posters for a visually appealing interface.

Summary:
The movie recommendation system leverages text vectorization and cosine similarity to provide personalized movie suggestions. 
