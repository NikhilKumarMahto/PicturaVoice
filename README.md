# PicturaVoice

Welcome to the PicturaVoice! This React Native application leverages the power of OpenAI's DALL-E and ChatGPT APIs to generate images and provide advanced text interactions. The app also features speech-to-text and text-to-speech capabilities, ensuring a comprehensive and responsive user experience across platforms.

Features
React Native: Cross-platform mobile app development.
ChatGPT API: Text interaction and AI conversation.
DALL-E API: AI-based image generation.
Speech to Text: Convert spoken words into text.
Text to Speech: Convert text into spoken words.
Responsiveness: Optimized for various screen sizes.
TailwindCSS (Nativewind): Utility-first CSS framework for styling.
Cross-Platform Compatibility: Runs smoothly on both iOS and Android.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/ai-image-generator.git
cd ai-image-generator
Install dependencies:

bash
Copy code
npm install
Set up environment variables:
Create a .env file in the root directory and add your OpenAI API keys:

env
Copy code
CHATGPT_API_KEY=your_chatgpt_api_key
DALLE_API_KEY=your_dalle_api_key
Run the app:

bash
Copy code
npm run start
npm run android  # for Android
npm run ios      # for iOS

Usage
AI Image Generation:

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
React Native: Framework for building native apps using React.
ChatGPT API: For natural language understanding and response generation.
DALL-E API: For generating images from textual descriptions.
Expo: For building and running React Native apps.
Nativewind: TailwindCSS for React Native.
React Native Voice: For speech-to-text functionality.
React Native TTS: For text-to-speech functionality.
Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

Fork the repository.
Create your feature branch:
bash
Copy code
git checkout -b feature/your-feature-name
Commit your changes:
bash
Copy code
git commit -m 'Add some feature'
Push to the branch:
bash
Copy code
git push origin feature/your-feature-name
Create a new Pull Request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
OpenAI for providing the DALL-E and ChatGPT APIs.
React Native community for continuous support and development.
Expo for an excellent React Native framework.
Nativewind for TailwindCSS integration in React Native.
Feel free to modify the template according to your project's specifics.
