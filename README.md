# Machine Learning Exoplanet

![1-Logo](Images/planets.jpg)

## Background
- Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
    - I Preprocessed the raw data
        - Preprocessed the dataset prior to fitting the model.
        - Performed feature selection and removed unnecessary features.
        - Used MinMaxScaler to scale the numerical data.
        - Separated the data into training and testing data.
    - Tuned the models
        - Used `GridSearch` to tune model parameters.
        - Tuned and compared classifiers.
## Comparing the models 
    - Deep Learning Model
      - created a deep learning model using tensor flow and keras 
          - Normal Neural Network - Loss: 0.26611795332981486
          - Accuracy: 0.883806049823761
    - Logistic Model
      - Used Hyperparameter Tuning/ Grid Search to tune the models parameters to try and get the highest accuracy 
        - Best Parameter: {'C': 10, 'penalty': 'l1'}
        - Best Score: 0.8793839585239402
        
    - Support Vector Machine 
      - Used Hyperparameter Tuning/ Grid Search to tune the models parameters to try and get the highest accuracy 
        - Best Parameter: {'C': 10, 'gamma': 0.0001}
        - Best Score: 0.8709972552607502
        
    
