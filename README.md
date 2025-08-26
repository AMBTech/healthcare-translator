🏥 **Healthcare Translation Web App with Generative AI**

A web-based prototype that enables real-time multilingual communication between patients and healthcare providers.
The app converts spoken input into text, generates accurate medical transcripts, translates them into the target language using Generative AI, and provides audio playback of the translated text.

This project was built as part of a pre-interview assignment to showcase rapid prototyping skills, AI integration, and full-stack development expertise.

✨ **Features**

🎤 Voice-to-Text – Capture patient or provider speech and transcribe it in real-time.

🌐 AI-Powered Translation – Translate transcripts between multiple languages with high accuracy, preserving medical terminology.

🔊 Text-to-Speech Playback – Play translated text using natural-sounding voices.

📱 Mobile-First Design – Optimized for both mobile and desktop devices.

📝 Dual Transcript Display – View original and translated text side by side.

🌍 Language Selection – Easily choose input and output languages.

🔒 Basic Security & Privacy – Transcripts are session-based, with no permanent storage.

🛠️ **Tech Stack**

Frontend/Backend: Next.js 14
 (TypeScript, App Router)

Styling: Tailwind CSS

Speech-to-Text: Web Speech API / Google Speech-to-Text

Translation: OpenAI API (Generative AI)

Text-to-Speech: Google Cloud Text-to-Speech API

Deployment: Vercel

🚀 **Deployment**

🔗 Live Demo: [Coming Soon]

⚙️ **Setup & Usage**

Clone the repository:
```
git clone https://github.com/your-username/healthcare-translator.git
cd healthcare-translator
```

Install dependencies:
```
npm install
```

Set up environment variables in .env.local:
```
OPENAI_API_KEY=your_openai_api_key
GOOGLE_APPLICATION_CREDENTIALS=./keys/gcp-tts.json
```

Run development server:
```
npm run dev
```

Open ```http://localhost:3000```
 in your browser.

⚠️ Disclaimer

This prototype is for demonstration purposes only and is not intended for official medical use. Patient confidentiality and privacy should be ensured in any production deployment.