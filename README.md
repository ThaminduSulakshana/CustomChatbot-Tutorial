# CustomChatbot-Tutorial

CustomChatbot-Tutorial repository! This tutorial provides a step-by-step guide on implementing a chatbot using language embeddings and FAISS (Facebook AI Similarity Search) for efficient information retrieval. Whether you're a beginner or an experienced developer, this tutorial will walk you through the process of building a custom chatbot for handling various use cases related to machine learning lectures.

## 🚀 Key Features

- **Data Loading:** Read data from an Excel and PDF file using pandas.
- **Text Preprocessing:** Split text into chunks using the SpacyTextSplitter.
- **Text Encoding:** Utilize the SentenceTransformer to encode text chunks into vectors.
- **FAISS Indexing:** Build a FAISS index with the encoded vectors for fast similarity search.
- **Interactive Search:** Allow users to interactively input questions, perform searches, and display relevant information.
- **Example Searches:** Demonstrate sample search queries, displaying nearest matching results and distances.


## 🛠️ Getting Started

Follow these steps to set up your environment and start building with LangChain:

1. Install dependencies: `pip install -r requirements.txt`.
2. Run the provided code snippets to instantiate models, create prompts, build chains, and set up Vector Stores.

## Use Cases

This tutorial is designed to handle various use cases related to machine learning lectures, including quick retrieval of information, interactive searching, and efficient handling of frequently asked questions (FAQs).

## Example

Explore the provided examples in each script to understand how to use the chatbot for interactive searches and information retrieval.

# Sample search query
query = "natural language processing techniques"
# Display nearest matching results and distances
search_loop(query)


**Note:** Ensure that you have the necessary permissions and licenses for the models and libraries used in this tutorial.

Happy coding! If you have any questions or feedback, feel free to reach out.
