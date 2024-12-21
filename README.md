# 🍽 ChefMate-Restaurant-Clustering-Cooking-Guide-Application 🍽 #
ChefMate is an intelligent application designed to cluster and recommend restaurants based on user preferences, such as favorite dishes or cuisines. It also features a chef-inspired chatbot that assists users with recipes, enhancing their cooking experience. The project leverages machine learning and cloud computing technologies to deliver personalized recommendations and culinary guidance.
## 🌟 Features of app
- **Personalized Recommendations:** Get tailored restaurant suggestions curated around your favorite dishes and cuisines.  
- **Interactive Maps:** Explore restaurants with dynamic maps and ratings for a more engaging experience.  
- **Cooking Assistance:** Engage with our chatbot for comprehensive, step-by-step recipe guidance and cooking tips.  
- **Future Integrations:** Upcoming features include seamless integration with food delivery platforms for hassle-free ordering.
## 🚀 Technologies Used
- **Streamlit:** Utilized for building an intuitive and user-friendly web application interface.  
- **AWS Services:** Employing S3 for data storage, RDS for database management, and EC2 for application deployment.  
- **Machine Learning:** Implementing clustering algorithms to provide precise restaurant recommendations.  
- **Python:** The primary programming language for application development.  
- **Chatbot Integration:** Enhancing user interaction with conversational AI capabilities.
## 🗝 Key Features of the project
- **Data Storage:** AWS S3 was employed to store project files and raw datasets securely.  
- **Data Preprocessing:** Conducted thorough data cleaning and preprocessing to ensure the datasets were ready for model training.  
- **Database Management:** Utilized AWS RDS to store cleaned datasets, enabling efficient and scalable querying.  
- **Model Training:** Designed and trained multiple clustering models, including:  
  - KMeans  
  - DBSCAN  
  - Agglomerative Clustering  
  - Gaussian Mixture  

- **Model Evaluation:** Assessed the performance of clustering models using the silhouette score to determine the best fit.  
- **Application Development:** Developed the ChefMate application using Streamlit to meet project objectives.  
- **Chatbot Integration:** Integrated a Gemini generative AI role-based chatbot via API key for interactive user assistance.  
- **Deployment:** Successfully deployed the application on AWS to support real-time user engagement.  
# 📊 Project Structure
The project follows the directory structure outlined below:

### 🧪 *Description of Each Component:*
Here’s the structured format with emojis for better clarity:  

- **📜 *ChefMate.py:*  
  The main entry point of the application. It initializes the Streamlit web app, processes user inputs, and displays restaurant recommendations along with chatbot interactions.**  

- **📦 *requirements.txt:*  
  Contains a list of all the Python packages and dependencies needed to run the application. Dependencies can be installed using `pip`.**  

- **📂 *ChefMate/:*  
  Holds datasets used in the project. The `Zomato_cluster_data.csv` file contains detailed restaurant information, including names, locations, cuisines, ratings, and other relevant details.**  

- **📁 *models/:*  
  A directory for storing machine learning models. The `kmeans_model.pkl` file contains the trained clustering model used for grouping restaurants based on user preferences.**  

- **🛠️ *ChefMate/:*  
  Includes scripts for data preprocessing and other utility functions.**  

- **📝 *data_preprocessing.ipynb:*  
  A notebook for cleaning raw restaurant data, handling missing values, and converting JSON data into a structured format for analysis.**  

- **🧹 *data_cleaning.ipynb:*  
  Contains reusable utility functions for data manipulation and visualization tasks within the application.**  

- **📖 *README.md:*  
  Provides detailed project documentation, including an overview, key features, installation steps, usage instructions, and contribution guidelines.**  
