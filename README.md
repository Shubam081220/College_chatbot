College Chatbot

An intelligent chatbot for college-related queries, built using Streamlit and fine-tuned T5 model. It supports both open-ended question answering and FAQ-style fallback responses using fuzzy matching.

Features

-  Answer open-ended questions using a fine-tuned T5 model
-  Fuzzy-matching for college FAQs
-  Streamlit-based interactive UI
-  Planned support for chat history context memory
-  PDF export for chat responses (coming soon)

Tech Stack

| Component       | Tech Used          |
|----------------|--------------------|
| Frontend       | Streamlit          |
| Backend Model  | T5 Transformer     |
| Matching Logic | FuzzyWuzzy / RapidFuzz |
| NLP Libraries  | Transformers, Datasets |
| Language       | Python             |


Getting Started

# Clone the repo
git clone https://github.com/Shubam081220/College_chatbot.git
cd College_chatbot

# Create and activate a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate   # On Windows

# Install dependencies
pip install -r requirements.txt

# Run the model on streamlit
streamlit run chatbot.py
