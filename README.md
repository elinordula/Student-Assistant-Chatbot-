Student Assistance Chatbot
An AI-powered chatbot designed to assist students with academic inquiries, department details, and general campus information using Natural Language Processing (NLP) and Machine Learning (ML).

Features
Intent Recognition: Classifies user queries using predefined intents stored in a JSON file.

Text Preprocessing: Tokenization, punctuation removal, and stopword filtering for improved query understanding.

Department & Member Identification: Extracts names and determines relevant departments dynamically.

TF-IDF Vectorization & Logistic Regression: Transforms input text into numerical features and predicts user intent.

Fallback Handling: Guides users to an external form for unresolved queries.

Streamlit Integration: Provides an interactive web-based interface for real-time responses.

Technology Stack
Python (Core chatbot development)

NLTK (Tokenization and text processing)

Scikit-learn (Machine Learning-based intent classification)

Streamlit (Interactive UI for student interaction)

JSON (Structured intent and department data storage)

Installation & Setup
Prerequisites
Ensure you have Python 3.x installed along with the required dependencies.

Steps
Clone the repository:

bash
git clone https://github.com/your-username/student-assistant-chatbot.git
cd student-assistant-chatbot
Install dependencies:

bash
pip install -r requirements.txt
Run the chatbot interface:

bash
streamlit run chatbot.py
Usage
Open the Streamlit UI.

Enter a query related to department members, academic schedules, or campus resources.

View real-time responses based on pre-trained intent classification.

If the chatbot cannot provide an answer, follow the provided fallback link to submit a query.
