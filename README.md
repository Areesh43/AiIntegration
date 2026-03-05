# AI Document Assistant

## Model Name & Source
**Model:** `gemini-3-flash-preview`  
**Source:** Google GenAI API ([google-genai Python SDK](https://pypi.org/project/google-genai/))

## Rationale for Selection
The `gemini-3-flash-preview` model was selected for its strong capabilities in natural language understanding and document-specific question answering. 
This model allows the assistant to provide accurate, context-aware responses strictly based on uploaded documents, ensuring relevant and precise information retrieval for users without relying on external data. 
Its integration with Google’s GenAI ecosystem also simplifies API usage and document management, making it suitable for a lightweight, interactive Streamlit application.

## Responsible AI Reflection (100–150 words)
Using AI responsibly means ensuring the model’s responses are accurate, transparent, and respectful of user privacy. 
In this project, the AI is restricted to answering questions based solely on the uploaded documents, preventing it from hallucinating information or exposing external content. 
This design encourages accountability by informing users when the answer is not present in the document. Additionally, sensitive data is handled cautiously, uploaded temporarily for processing without storing personal information long-term. 
Ethical considerations also include clear user guidance on AI limitations, avoiding over-reliance, and maintaining human oversight in interpreting results. 
By implementing these principles, the application demonstrates responsible AI deployment—maximizing utility while minimizing risks associated with misinformation, data misuse, or unintended bias.
