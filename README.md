Movie Recommender System Using Machine Learning!
<img src="demo/6.jpeg" alt="workflow" width="70%">
Recommendation systems are essential tools in today’s busy world. They help users make efficient choices by providing personalized recommendations based on their profiles, browsing history, and preferences.

This project demonstrates a machine learning-based movie recommendation system, allowing users to discover movies similar to their interests. It leverages Streamlit for the interface and combines advanced techniques for recommendation generation.

Types of Recommendation Systems:
1. Content-Based:
Utilizes item attributes to form recommendations based on what the user has interacted with.
Example: Recommendations based on genres, actors, or directors of movies previously watched.
Challenges: Over-specialization can lead to obvious or overly narrow recommendations.
2. Collaborative Filtering:
Builds clusters of users with similar interests or ratings to generate recommendations.
Example: "Users who liked this movie also liked..."
Challenges: Computationally expensive and biased toward popular items, leaving new or niche items unconsidered.
3. Hybrid Systems:
Combines content-based and collaborative filtering approaches to overcome their limitations.
Widely used due to its balance and effectiveness.
Dataset Used:
TMDB Movie Dataset: Includes metadata for movies such as genres, keywords, and popularity scores.
Algorithm Used: Cosine Similarity
Measures similarity between two vectors (e.g., movie feature vectors).
Generates a score between [0, 1], where:
1 indicates complete similarity.
0 indicates complete dissimilarity.
For details, check this resource.
Demo:
<img src="demo/1.png" alt="workflow" width="70%"> <img src="demo/2.png" alt="workflow" width="70%"> <img src="demo/3.png" alt="workflow" width="70%">
How to Run the Project?
Steps:
Clone the repository:

bash
Copy code
https://github.com/ShaikSameer18/Movie-Recommender-System-Using-Machine-Learning/upload/main
Create a Conda environment:

bash
Copy code
conda create -n movie python=3.7.10 -y
Activate the environment:

bash
Copy code
conda activate movie
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Generate the model by running:

bash
Copy code
Movie Recommender System Data Analysis.ipynb
Run the application:

bash
Copy code
streamlit run app.py
Author:
Sameer Shaik
This project is licensed under the MIT License.