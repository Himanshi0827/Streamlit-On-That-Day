# Streamlit-On-That-Day
Streamlit web application, "On That Day..."
# Overview
This Streamlit web application, "On That Day...", is designed to provide information about a celebrity. It uses Google's Generative AI (Gemini) to fetch details such as the person's biography, date of birth, and major events around that date in history.

# Components
Streamlit Interface: The web app provides a text input field where users can enter the name of a celebrity they want to learn about.

# Google Generative AI (Gemini): 
The application leverages Google's Generative AI model (Gemini) to generate responses based on user queries.

# Prompt Templates: 
The app uses prompt templates to structure queries to the Gemini AI. These templates include variables like name, person, dob (date of birth), and description.

# LLM Chains: 
The code defines LLM chains using the LLMChain and SequentialChain classes to orchestrate multiple queries and responses to gather comprehensive information about the celebrity.

# Installation and Setup
# Install the required libraries using pip:


pip install streamlit langchain_google_genai langchain
Obtain a Google API Key for Gemini and set it in your environment variables as GOOGLE_GEMINI_AI.

# Run the Streamlit app using the following command:

arduino

streamlit run app.py
Enter the name of a celebrity in the text input field and click submit to fetch information.

Usage
Upon running the app, you'll see the input field for entering the celebrity's name.
Enter the name and submit the form.
The app will fetch and display details such as the celebrity's biography, date of birth, and major events around that date.
Code Structure
app.py: Main Streamlit application code that defines the UI and integrates with the Google Generative AI.
README.md: Documentation file (this file) providing an overview, installation instructions, usage guidelines, and code structure.
