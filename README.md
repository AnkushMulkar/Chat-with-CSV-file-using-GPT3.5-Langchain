## Chat-with-CSV-file-using-GPT3.5-Langchain🦜🔗

## Overview

The "Ask the Data App" is an interactive tool built with Streamlit that allows users to query data from CSV files using natural language. It utilizes the Langchain library and the GPT-3.5 Turbo language model by OpenAI to provide responses to data-related queries, making it a valuable tool for data exploration and analysis.

### Key Features

- Load and view CSV files directly within the app.
- Query data using natural language questions.
- Utilize the GPT-3.5 Turbo language model for generating responses.
- Securely input your OpenAI API key.
- Designed for efficient data exploration and analysis.

## Getting Started

To run the Ask the Data App locally, follow these steps:

1. Clone this repository to your local machine.

2. Install the required Python packages using pip:

   ```
   pip install streamlit pandas langchain
   ```
Run the application using Streamlit:
```
streamlit run app.py
```
The application will open in your default web browser.

Usage
Upon launching the application, you can upload a CSV file using the "Upload a CSV file" button.

Choose from predefined query examples or enter your custom query in the "Enter your query" field.

Provide your OpenAI API Key in the respective input box.

The app will generate responses to your queries based on the data from the uploaded CSV file and display them in the "Output" section.

## Technologies Used
Streamlit: A fast, open-source app framework for creating interactive web applications.
Pandas: A data manipulation library for data analysis.
Langchain: A library for interacting with language models, including GPT-3.5 Turbo.
OpenAI: The GPT-3.5 Turbo language model is used to answer natural language queries.
## Credits
Application Designed By [Ankush Mulkar]
