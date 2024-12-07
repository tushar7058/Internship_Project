# Chatbot Using NLP

This project implements a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to understand user intents and provide appropriate responses based on predefined patterns. It leverages popular Python libraries for NLP, machine learning, and an interactive web interface.

## Features
- **Intent Recognition**: Understands user intents like greetings, farewells, gratitude, and more.
- **Dynamic Responses**: Provides relevant responses based on user input.
- **Conversation History**: Logs and maintains a conversation history for later review.
- **Interactive Web Interface**: Built with Streamlit for user-friendly interaction.
- **Customizable Intents**: Modify or extend chatbot behavior through an easily editable `intents.json` file.

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - [NLTK](https://www.nltk.org/): For natural language processing tasks.
  - [Scikit-learn](https://scikit-learn.org/): For machine learning.
  - [Streamlit](https://streamlit.io/): For creating an interactive web interface.
  - JSON: For storing chatbot intents and responses.

## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>

2. Create a Virtual Environment (Optional but Recommended)
python -m venv venv
# Activate the environment
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Required Packages
pip install -r requirements.txt

4.Download NLTK Data
import nltk
nltk.download('punkt')


Usage
Run the Chatbot Application
streamlit run app.py


Customization

Intents Data

The chatbot’s behavior is defined in the intents.json file, which contains:
	•	Tags: Categories of user input (e.g., “greeting”).
	•	Patterns: Example phrases the chatbot recognizes.
	•	Responses: Predefined replies the chatbot provides.

You can modify intents.json to add new tags, patterns, and responses, tailoring the chatbot to your needs.

Conversation History

The chatbot logs conversations in a CSV file (chat_log.csv). This can be accessed via the “Conversation History” option in the Streamlit sidebar.

Contribution

Contributions are welcome! If you have ideas for improvements or new features:
	1.	Fork this repository.
	2.	Create a new branch for your feature or fix.
	3.	Submit a pull request with detailed explanations.

License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of this license.

Acknowledgments
	•	NLTK for providing essential NLP tools.
	•	Scikit-learn for machine learning support.
	•	Streamlit for enabling a simple and powerful web interface.


Author

Developed by Tushar kale 
