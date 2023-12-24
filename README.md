# LinguoGenius RAG Orchestrator 2 @Nokathon

This repository contains an advanced Retrieval-Augmented Generation (RAG) system, integrating TruLens for feedback-driven evaluation, Flask for a user-friendly web interface, and Sentence Window Indexing to enhance document retrieval.

## Overview

The system is designed to provide an intuitive platform for users to upload documents, build a Sentence Window Index, and query the system for insightful responses. It leverages TruLens for accurate evaluation metrics and Flask to create a seamless web experience.

## Components

1. TruLens Integration

   * Utilizes TruLens for Answer Relevance, Context Relevance, and Groundedness evaluation.
   
   * Requires OpenAI and Hugging Face API keys provided through environment variables.
   
2. Sentence Window Indexing

   * Implements a specialized Sentence Window Index for efficient document processing.
   
   * Uses Flask to create a responsive web interface for user interaction.
   
3. Flask Web Interface

   * Allows users to upload documents seamlessly and build the Sentence Window Index.
   
   * Provides an intuitive query system to retrieve responses from the indexed documents.
   
## Usage

### Prerequisites
   
* Python 3.x

* Pip package manager

### Installation
   
Clone the repository:

```
git clone https://github.com/Zeros2112/advanced-rag-system.git
cd advanced-rag-system
```

Install dependencies:

```
pip install -r requirements.txt
```

## Running the Application

1. Set up environment variables:

* Rename the .env.example file to .env.

* Add your OpenAI and Hugging Face API keys to the .env file.

2. Run the Flask application:

```
python app.py
```

3. Access the web interface:
Open your browser and navigate to http://localhost:5000.


## Web Interface
* Home: Displays the main page with options to upload a document and build the Sentence Window Index.

* Upload Document: Allows users to upload documents for processing.

* Generate Response: Accepts user queries and provides responses based on the Sentence Window Index.

## Contributors

* Nguyen Gia Hy

## Acknowledgements

* Special thanks to TruLens for their comprehensive evaluation framework.

* Flask for simplifying web development.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
