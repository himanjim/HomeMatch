# Real Estate Listings Generation and Search with AI and ChromaDB
This repository contains a Python notebook project that utilizes AI to generate real estate listings and implement a vector-based search system using ChromaDB. The project uses **LangChain** and **OpenAI** models to create and store real estate listings, then applies semantic search to match listings with user preferences.

## Overview
The project demonstrates how to generate real estate listings using a Large Language Model (LLM), store the listings in a vector database for efficient retrieval, and perform semantic search based on user queries. It also showcases how embeddings and machine learning techniques can enhance the accuracy of real estate recommendations.

### Key Features
- **AI-Powered Listing Generation**: Generates detailed real estate listings using OpenAI's GPT-3.5 model.
- **Vector Database**: Utilizes ChromaDB to store real estate listings with semantic embeddings for efficient retrieval.
- **Semantic Search**: Implements a search mechanism that retrieves listings based on user preferences and semantic similarity.

## Files in the Repository

- **HomeMatch.ipynb**: Main Jupyter Notebook that includes code for:
  - Generating real estate listings using OpenAI's GPT model.
  - Storing and processing listings in a vector database (ChromaDB).
  - Performing semantic search based on user queries.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone <your-repository-link>
   ```

2. **Install Dependencies**: Install the necessary Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**: Open and execute the Jupyter Notebook to:
   - Generate real estate listings.
   - Store the listings in ChromaDB.
   - Perform semantic search based on user preferences.

4. **Customization**: Modify the prompts and the number of listings generated as needed.

## Requirements

- Python 3.x
- Jupyter Notebook
- OpenAI API Key
- Required Python libraries listed in the `requirements.txt`

## License

This project is licensed under the MIT License.
