**Setting Up Your GPT Bot**

To set up the GPT-based chatbot, follow these simple steps:

1. **Get an API Key**

   - Go to the OpenAI website and sign up for an API key if you don't have one already.
   - Once you have the API key, replace `<YOUR-API-KEY>` in the JavaScript code with your actual API key.

2. **Edit the Assistant's Role**

   - In the code, you'll notice a system message defining the assistant's role. Modify this message to suit your chatbot's purpose.

   Replace `<YOUR-ASSISTANT-NAME>` with your chatbot's name and `<YOUR-INSTRUCTIONS>` with your specific instructions. For example:

   ```json
   {
     "role": "system",
     "content": "You are an AI assistant named EduBot. Your job is to provide detailed explanations for math and science questions, but don't provide answers to general knowledge questions."
   }
   ```

