# AI-Powered Book Retrieval and Summarization Engine

## Overview
This repository contains an AI-powered engine designed to enhance book retrieval and summarization, tailored for university and academic environments. By utilizing state-of-the-art technologies like **Milvus**, **Hugging Face**, and **Python**, the system efficiently processes queries to retrieve and summarize books, research papers, and other academic resources. Its scalability makes it ideal for handling large datasets in indoor settings like libraries and research centers.

---

## Features

- **Semantic Search**: Leverages Milvus vector database for high-performance semantic search.
- **AI Summarization**: Uses Hugging Face models to generate concise and meaningful summaries.
- **Multi-Source Retrieval**: Supports URLs, YouTube links, and other online sources for diverse data inputs.
- **Scalability**: Optimized for large academic datasets, ensuring seamless performance.
- **Privacy and Security**: Processes sensitive academic data with secure protocols.

---

## Prerequisites

- **Python 3.8+**
- **Milvus**
- **Sentence Transformers**
- **Hugging Face Transformers**
- **Gradio**

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-book-retrieval.git
   cd ai-book-retrieval
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Milvus:
   Follow the [Milvus installation guide](https://milvus.io/docs/install_standalone.md) to set up your database.
4. Configure API keys:
   - Add your Hugging Face API key for summarization.
   - Set up a Milvus instance and update connection settings in `config.py`.

---

## Usage

### 1. Running the Engine

Start the application:
```bash
python app.py
```

### 2. Access the Gradio Interface
The Gradio interface will launch in your default browser. Enter queries to retrieve and summarize academic resources.

---

## Example Workflow

1. **Input**: Enter a query, e.g., `"Introduction to quantum physics."`
2. **Processing**:
   - The system uses Sentence Transformers to generate query embeddings.
   - Milvus retrieves semantically similar resources from the database.
   - Hugging Face models summarize the retrieved content.
3. **Output**: The Gradio interface displays the top results with descriptions, summaries, and links.

---

## Scalability

The engine is designed to scale across large datasets, handling:
- Indoor university resources like lecture notes and research papers.
- Millions of entries using Milvus’s high-performance indexing.

---

## Contribution
We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- [Milvus](https://milvus.io/)
- [Hugging Face](https://huggingface.co/)
- [Gradio](https://gradio.app/)

For questions or feedback, please open an issue or contact us at [support@yourdomain.com](mailto:support@yourdomain.com).
