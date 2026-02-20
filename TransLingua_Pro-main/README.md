# TransLingua_Pro

A Streamlit application designed for real-time language translation. The app supports multiple input methods including text input, file uploads, and voice input. Users can translate text between various languages and listen to the translated text through audio feedback. The interface is interactive and features a customizable background.

## Features

- **Real-Time Language Translation**: Enter text and get instant translations between selected languages.
- **File Upload and Translation**: Upload text or Word files for translation.
- **Voice Input Translation**: Record your voice, transcribe it, and translate it to the selected language.
- **Audio Feedback**: Option to listen to the translated text in audio format.
- **Customizable Background**: Set a background image for the app interface.

![Alt text](trans.png)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/MurakondaPavani/translingua-ai-translator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd TransLingua_Pro-main
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Create a .env file and add your Groq API Key:
    GROQ_API_KEY=your_api_key_here
   
5. Run the application:
    streamlit run app.py

## Usage

1. Open the app in your web browser at `http://localhost:8501`
2. Select source and target languages
3. Enter the text.
4. Click the Translate button.

## Dependencies

- `streamlit`
- `langchain_openai`
- `langchain_core`
- `langchain_groq`
- `gtts`
- `speech_recognition`
- `docx`
- `python-dotenv`

## Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements.
## 🎥 Project Demo Video

Watch the demo video here:
https://drive.google.com/file/d/1lCTM65AMGRQ0lymYaX80VBpos3dqxFrc/view?usp=sharing
