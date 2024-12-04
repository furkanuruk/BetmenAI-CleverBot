#  BetmenAI-CleverBot
 This repository contains a chatbot application integrating Cleverbot, Google Translate, and text-to-speech functionalities.

## Requirements  

Before running the application, ensure the following Python libraries are installed:  

- [cleverbotfree](https://pypi.org/project/cleverbotfree/)  
- [googletrans](https://pypi.org/project/googletrans/)  
- [gTTS](https://pypi.org/project/gTTS/)  
- [playsound](https://pypi.org/project/playsound/)  
- [speech_recognition](https://pypi.org/project/SpeechRecognition/) (optional)  

Install dependencies using:  

bash
pip install -r requirements.txt

Code Overview
speak(text)
Converts text into Turkish speech and plays it using gTTS and playsound.

translate_text(who, text, lang)
Translates text to the specified language and displays the output.

Chat Loop
Handles user input, translation, bot interaction, and audio playback in a continuous loop until "quit" is entered.

Potential Improvements
Implement live speech-to-text input for seamless audio conversations.
Expand language support for broader usability.
Enhance error handling and performance optimization.
