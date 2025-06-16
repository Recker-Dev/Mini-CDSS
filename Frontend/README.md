# Mini-CDSS Application

## BACKEND CODE: [https://github.com/Recker-Dev/Mini-CDSS-FastAPI]

## Overview

This is a Streamlit-based application designed to assist doctors in initial patient encounters. The application generates an initial patient report, provides diagnoses, and utilizes Tavily Web Search to find relevant best practices.

## Features

- Generate initial patient reports based on input data
- Provide preliminary diagnoses
- Search for best practices using Tavily Web Search
- Extract medical insights from uploaded documents
- RAG-Chat with uploaded documents
- Use vision models to analyze uploaded images and provide insights
- Offer feedback mechanisms for refining outputs

## Installation

To run this application locally/cloud, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pip

### Setup

```bash
# Clone the repository
git clone https://github.com/Recker-Dev/Mini-CDSS-Streamlit-Frontend.git
cd Mini-CDSS-Streamlit-Frontend
```

# Install dependencies

```bash
pip install -r requirements.txt
```

## Running the Application

```bash
streamlit run app.py
```

## Usage

1. Open the application in your browser at `http://localhost:8501` and enter and validate the API Keys.
2. Upload patient data or documents
3. Review generated reports and diagnoses
4. Query images using the vision model
5. Access relevant best practices

## Deployment

To deploy this application on Streamlit Cloud or any hosting service, follow these steps:

1. Change the api-endpoint of FASTAPI of yours, Backend Code [https://github.com/Recker-Dev/Mini-CDSS-FastAPI]
2. Deploy Application on Streamlit Cloud.
3. .env vars should be in Backend side and not on Streamlit side.

## 📝 License

This project is licensed under the MIT License.

## 📬 Contact

For any issues or suggestions, reach out at [reckerdev@gmail.com](mailto:reckerdev@gmail.com).
