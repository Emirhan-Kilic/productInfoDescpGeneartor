# Product Name & Description Generator

Produced For Trendyol E-Commerce Hackathon in Teknofest 2024

This project utilizes the LLaMA (Large Language Model) 3.1 to automatically generate product names and descriptions based on user input. Key features include:

Model Loading: Loads a pre-trained LLaMA model and tokenizer, optimized for memory efficiency with 4-bit quantization.

Data Handling: Extracts product examples from a CSV file, including input texts, product name suggestions, and descriptions.

Relevant Example Retrieval: Utilizes a Retrieval-Augmented Generation (RAG) approach with TF-IDF to find the most relevant example based on user input, ensuring contextually appropriate suggestions.

Prompt Engineering: Constructs structured prompts guiding the model to generate clear product outputs.

Response Generation: Generates responses using the model with configured settings to enhance creativity and coherence.

Multilingual Translation: Integrates the deep-translator library for translating generated descriptions into various languages.

User Interaction: Prompts for user input and desired translation language, displaying available options clearly.
