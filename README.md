Movie Recommender System Using Machine Learning!
Workflow:
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




How to Run the Project?
Steps:
Clone the repository:

bash
Copy code
https://github.com/ShaikSameer18/Movie-Recommender-System-Using-Machine-Learning
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

OUTPUT

![image](https://github.com/user-attachments/assets/6f900bcc-af39-4173-9ace-4e76ed594a7a)
![Screenshot 2025-04-17 170208](https://github.com/user-attachments/assets/5f8859f9-d5c6-4dff-95ea-cfad70e5fc20)
![Screenshot 2025-04-17 171418](https://github.com/user-attachments/assets/818bc07b-9572-4f47-b94e-664abb278096)
![Screenshot 2025-04-17 171434](https://github.com/user-attachments/assets/e7523f18-d549-4e8c-acce-98d650339770)
![Screenshot 2025-04-17 171451](https://github.com/user-attachments/assets/33027ad3-97fa-4afd-a70a-2585d3b7ddf4)




