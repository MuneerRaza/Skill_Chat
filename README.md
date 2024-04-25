# Muneer Raza's Personal Portfolio Chatbot

## Overview
This repository contains the code and resources for a Retrieval-Augmented Generation (RAG) chatbot designed to act as a personal portfolio assistant for Muneer Raza. The chatbot leverages the Llama-2-7b model from HuggingFace and a custom vector index to provide detailed information about Muneer's skills, projects, and professional journey.

## Features
- **Personalized Responses:** Tailored to showcase Muneer Raza's academic and professional background.
- **Advanced NLP:** Utilizes the latest LLMs for natural language understanding and generation.
- **Contextual Awareness:** Maintains conversation context for coherent and relevant interactions.

## Project Structure
- `llama_index/`: Core directory containing the LlamaIndex implementation.
- `models/`: Serialized models and configuration files.
- `scripts/`: Utility scripts for setup and deployment.
- `VectorDB source.txt`: Text file with vector data for the chatbot's knowledge base.

## Setup
To set up the project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the setup script with `python scripts/setup.py`.

## Usage
To interact with the chatbot:
1. Start the chatbot server with `python app.py`.
2. Open your browser and navigate to `http://localhost:5000`.
3. Use the chat interface to ask questions about Muneer Raza.

## Technologies Used
- **Python:** Primary programming language.
- **PyTorch:** For model quantization and neural network operations.
- **HuggingFace Transformers:** For accessing pre-trained LLMs.
- **LlamaIndex:** For creating and querying the vector index.

## Contributions
Contributions are welcome! Please read the `CONTRIBUTING.md` file for guidelines on how to contribute to this project.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments
- HuggingFace for providing access to state-of-the-art language models.
- The LlamaIndex community for their support and contributions.

