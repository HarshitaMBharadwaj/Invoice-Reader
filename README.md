# Gemini Image Processing Demo

This project is a chatbot application using Google's Gemini model to process image-based invoices and answer questions related to them. The chatbot can understand and interpret the content of uploaded invoices, providing relevant responses based on both image and text inputs.

## Features
- **Image Upload and Display**: Allows users to upload images of invoices (JPG, JPEG, PNG), which are displayed in the Streamlit interface.
- **Question Answering**: Users can input questions related to the uploaded invoice, and the chatbot provides contextual answers based on the invoice content.
- **Invoice-Specific Prompting**: The chatbot uses a pre-defined prompt to help guide responses specifically toward understanding invoices.

## Software and Libraries Used
- **Python**: Core language for backend processing.
- **Streamlit**: Web interface framework to enable easy interaction with the chatbot.
- **Google Generative AI (Gemini Model)**: Used for generating responses based on image and text input. This project uses the `gemini-1.5-flash` model.
- **PIL (Python Imaging Library)**: Used for image processing.
- **dotenv**: To manage environment variables securely.
- **Google API**: Integrates with Google’s AI platform to enable content generation.

## Use Case
This application is tailored for invoice processing, specifically for businesses and individuals looking to automate the understanding of invoice details. By uploading an invoice and asking questions about it, users can quickly gain insights, making it easier to track and interpret invoice data without manually reviewing each document.


## Project Structure
- `app.py`: Main application file for running the chatbot interface.
- `requirements.txt`: Txt file that contains all the required libraries for the project.
- `.env`: Store your API key here for secure access.
- `README.md`: Project documentation.

## Conclusion 

The Gemini Image Processing Demo serves as a powerful tool for automating invoice data extraction and interpretation. By leveraging advanced generative AI from Google’s Gemini model, the application simplifies the often tedious task of reviewing and understanding invoice details. This project showcases the potential of AI in transforming document management, saving time and reducing errors. As AI continues to evolve, this application can be further enhanced to support a broader range of documents, making it a versatile asset for businesses and individuals alike. With future updates and extended capabilities, the Gemini Image Processing Demo holds promise as a foundation for robust, AI-driven document analysis solutions.
