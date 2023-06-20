This project is made for a submission in the Hack-AI-thon conducted by karpagam college of engineering

## Concept
This simple crop recommender system was trained using Random Forest Algorithm in giving recommendations to farmers the best and suitable crop based on an Indian Crop Recommendation Dataset.By inputing N, P, K, and pH values based on soil conditions, weather conditions such as temperature, humidity, and rainfall, and regional location, the system can recommend what the best and most suitable crop to plant.

## Tech stack
streamlit:To design the whole frontend and integrate the design,API and dataset
scikit-learn:Provides a selection of efficient tooles for machine learning and statistical modeling
sklearn.inspectTto help understand the predictions from a model and what affects them
weather API:To provise weather related inputs and reduse the load from user end 
dataset:https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

## Instructions
To run this web app on your system:
    1. Clone this repository
    2. Download and install all the requirements as stated in repo in the command prompt 
        ex:pip install <req>
    3. After that open command prompt and navigate to the folder
    4. On the command prompt :
        streamlit run app.py
    5. Then the app should open

now you can edit and experiment with it
