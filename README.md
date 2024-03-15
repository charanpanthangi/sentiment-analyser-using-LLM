

A Sentiment Analyser model using Gemini LLM is a powerful tool for asking questions and getting precise answers, utilizing the strengths of both large language models (LLMs) and advanced information retrieval methods. Here's a quick summary:

Key Ingredients:

Gemini LLM: This acts as the brain, leveraging its understanding of language and the world to process questions and generate meaningful responses.
Information Retrieval System: This combs through vast amounts of data efficiently, finding relevant information based on the question and the LLM's insights.
Workflow:

Ask a question: You pose your query in clear and concise language.
LLM analysis: The LLM breaks down your question, identifying key concepts and search parameters.
Information retrieval: The retrieval system scours through data sources, guided by the LLM's understanding, to find relevant answers.
LLM synthesis: The LLM receives the retrieved information and crafts a comprehensive and informative response, ensuring it's consistent with the source and addresses your original question.
Benefits:

Accurate answers: Leverages the power of both LLM understanding and efficient data retrieval for better accuracy.
Variety of data sources: Can access and integrate information from various sources, providing a wider perspective.
Natural language response: Generates answers in a human-like, easy-to-understand manner.
Adaptability: Can be trained on specific domains or tasks for even more focused expertise.
Overall, a QA model using Gemini LLM represents a sophisticated approach to question answering, promising precise and informative responses to your inquiries.


## Dependencies and Installation
----------------------------
To install the MultiPDF Chat App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from Gemini  and add it to the `.env` file in the project directory.
```commandline
Gemini_API_KEY=your_secrit_api_key
```

## Usage
-----
To use the Sentiment Analyser App, follow these steps:

1. Ensure that you have installed the required dependencies and added the Gemini API key to the `.env` file.

2. Run the 
   ```
   streamlit run Sentiment Analyser.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.

