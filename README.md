# LSTM-Next-Word-Prediction

This project implements a **Next Word Prediction** system using a Long Short-Term Memory (LSTM) model. It predicts the next word in a sentence based on a given sequence of words. The model is trained on textual data and can be tested with various inputs to explore its predictive capabilities.


## Project Overview

Next Word Prediction is a common application of Natural Language Processing (NLP) that has many real-world applications, including:

- Autocomplete in text editors.

- Personalized content suggestions.

This project demonstrates how to build, train, and test an LSTM-based model for Next Word Prediction. It also includes an interactive Streamlit application for easy user interaction.

## Dataset
The model is trained on the novel of "Antigone" by Jean Anouilh, a classic French play. The dataset was preprocessed to create sequences suitable for training an LSTM model.

## Installation

To set up the project, clone the repository and install the required packages:

```bash
git clone https://github.com/moaoutir/Next-Word-Prediction-Using-LSTM.git
cd Next-Word-Prediction-Using-LSTM
python -m venv venv            
source venv/bin/activate  
pip install -r requirements.txt 
```
## Run the Streamlit Application:

Launch the application using the following command:
```bash
streamlit run app.py
```
Open your web browser and navigate to http://localhost:8501 to interact with the app.
