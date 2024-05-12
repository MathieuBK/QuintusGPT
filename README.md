# QuintusGPT

QuintusGPT is a chatbot application that simulates a conversation with the french indie hacker Quentin Roiseux. The chatbot provides valuable IT & cybersecurity info/advice to users, drawing from both Quentin's experience and insights. It also has access to the transcriptions of all pages of [the ANSSI website](https://cyber.gouv.fr/) - the french National Agency for the Security of Information Systems - which are used to provide context and support for the chatbot's responses.


## Features

- Engage in a conversation with a chatbot that emulates Quentin's communication style.
- Receive focused, practical, and direct IT info/advices.
- Access relevant snippets from transcriptions of ANSSI's website pages to support the chatbot's responses.
- Utilize semantic search to find relevant content from the transcripts.


## Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenAI API key
- Pinecone API key and environment details

### Installation

1. Clone the repository:
```
git clone https://github.com/your-repo-url/QuintusGPT.git
```
2. Change to the project directory:
```
cd QuintusGPT
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Set up the environment variables:
- `OPENAI_API_KEY`: Your OpenAI API key
- `GROQ_API_KEY`: Your Groq API key
- `MONGO_DB_URI`: Your MongoDB URI connection string
- `MONGO_DB_DATABASE_NAME`: Your MongoDB database name
- `MONGO_DB_COLLECTION_NAME`: Your MongoDB database collection name
- `PINECONE_API_KEY`: Your Pinecone API key
- `PINECONE_ENVIRONMENT`: Your Pinecone environment details
- `PINECONE_INDEX_NAME`: Your Pinecone index details
- `PINECONE_ENDPOINT`: Your Pinecone endpoint


### Usage

1. Run the Streamlit app:
```
streamlit run app.py
```
2. Open the app in your web browser and enter your prompt to start the conversation with the chatbot. By default, Streamlit app will run on PORT 8501: 
- Local URL: http://localhost:8501
- Network URL: http://26.26.26.1:8501


## Contact

If you have any questions or need assistance, please feel free to reach out to me directly. You can contact Quentin Roiseux via [email](mailto:roiseux.quentin@laposte.net).


## Acknowledgments

- ANSSI for providing valuable information on their website (Please, don't sue me 😱 !)
- OpenAI for their language models and embeddings.
- AssemblyAI for providing a great Whisper API DX.
- Langchain for their text processing tools.
- Pinecone for their semantic search capabilities.
- Streamlit & its amazing community for developing such great framework.
- Merops SAS for supporting this project
- Python for being such an amazing language ❤️
