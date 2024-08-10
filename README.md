# ✨ Simple ChatBot Using Google Generative AI ✨

This Python script simulates a simple chatbot using Streamlit for the user interface and Google Generative AI for generating responses. The chatbot allows users to interact by sending messages and receiving AI-generated replies.

## Features

### 1. Google Generative AI Integration
- **AI-Powered Responses**: The chatbot uses the `gemini-1.5-flash` model from Google's Generative AI suite to generate relevant and context-aware responses.

### 2. Streamlit Interface
- **User-Friendly UI**: The application features a clean, modern interface designed with Streamlit, providing a seamless experience for users.
- **Chat History**: Users can view the conversation history, with each user message and AI response displayed in a visually appealing format.

### 3. Real-Time Interaction
- **Instant Responses**: Users can input prompts and receive immediate AI responses in real-time.

### 4. Error Handling
- **Input Validation**: The system ensures that inputs are provided before attempting to generate a response, preventing errors and improving user experience.

## Implementation Details

### 1. Generative Model
- **Model Used**: The script uses the `gemini-1.5-flash` model from Google's Generative AI.

### 2. Chat Interface
- **Styled Messages**: User messages and bot responses are displayed in styled message bubbles, enhancing readability and the overall user experience.

### 3. Input Handling
- **Text Input**: The script uses Streamlit's form and text input to capture user messages.
- **Form Submission**: Upon submission, the chatbot generates a response, which is then added to the chat history.

## How to Use

### 1. Clone the Repository
Clone the repository containing the script.

```bash
git clone https://github.com/yourusername/simple-chatbot.git
cd simple-chatbot
```

### 2. Set Up API Key
Replace the placeholder `GOOGLE_API_KEY` in the script with your actual Google API key.

```python
GOOGLE_API_KEY = "your_actual_api_key"
```

### 3. Run the Script
Execute the script in a Python environment.

```bash
streamlit run chatbot.py
```

### 4. Interact with the Chatbot
Follow the on-screen prompts to enter your message and receive a response from the AI.

## Dependencies

- **Python 3.7+**
- **Streamlit**: For the web interface.
- **Google Generative AI Python SDK**: For accessing Google's AI models.

Install dependencies using:

```bash
pip install streamlit google-generativeai
```

## Example Usage

```bash
python chatbot.py
```

Replace `chatbot.py` with the filename where you've saved your script.

## Conclusion

This simple chatbot system demonstrates the integration of AI with a web-based interface. It serves as a foundation for building more complex AI-driven applications and offers a practical example of combining Python with modern AI technologies.

