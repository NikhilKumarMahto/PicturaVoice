# PicturaVoice

Welcome to the PicturaVoice! This React Native application leverages the power of OpenAI's DALL-E and ChatGPT APIs to generate images and provide advanced text interactions. The app also features speech-to-text and text-to-speech capabilities, ensuring a comprehensive and responsive user experience across platforms.

## Features
1. React Native: Cross-platform mobile app development.
2. ChatGPT API: Text interaction and AI conversation.
3. DALL-E API: AI-based image generation.
4. Speech to Text: Convert spoken words into text.
5. Text to Speech: Convert text into spoken words.
6. Responsiveness: Optimized for various screen sizes.
7. TailwindCSS (Nativewind): Utility-first CSS framework for styling.
8. Cross-Platform Compatibility: Runs smoothly on both iOS and Android.

## Installation
Clone the repository:

git clone https://github.com/yourusername/PicturaVoice.git

cd PicturaVoice 

Install dependencies:
npm install

Set up environment variables:
Create a .env file in the root directory and add your OpenAI API keys:

env
CHATGPT_API_KEY=your_chatgpt_api_key,
DALLE_API_KEY=your_dalle_api_key


## Run the app:

bash
npm run start
npm run android  # for Android
npm run ios      # for iOS

 ##Usage
### AI Image Generation:

Navigate to the image generation screen.
Enter a prompt and submit to generate an image using the DALL-E API.
AI Text Interaction:

Navigate to the chat screen.
Enter your query or use the speech-to-text feature to interact with ChatGPT.
Speech to Text:

Use the microphone button to convert speech to text in any input field.
Text to Speech:

Use the speaker button to convert any text response to speech.
Technologies Used
1. React Native: Framework for building native apps using React.
2. ChatGPT API: For natural language understanding and response generation.
3. DALL-E API: For generating images from textual descriptions.
4. Expo: For building and running React Native apps.
5. Nativewind: TailwindCSS for React Native.
6. React Native Voice: For speech-to-text functionality.
7. React Native TTS: For text-to-speech functionality.
   
## Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Fork the repository.
Create your feature branch:
git checkout -b feature/your-feature-name

Commit your changes:
git commit -m 'Add some feature'

Push to the branch:
git push origin feature/your-feature-name

Create a new Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
1. OpenAI for providing the DALL-E and ChatGPT APIs.
2. React Native community for continuous support and development.
3. Expo for an excellent React Native framework.
4. Nativewind for TailwindCSS integration in React Native.
5. Feel free to modify the template according to your project's specifics.
