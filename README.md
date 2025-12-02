# ❤️ Girlfriend AI – Voice-to-Voice AI Companion

An intimate, real-time voice-to-voice AI girlfriend powered by cutting-edge LLMs that listens to you, understands your emotions, and responds with a warm, affectionate, and naturally sounding female voice — just like a real girlfriend would.

### 🎙️ How It Works
1. **You speak** → Your voice is captured via the browser microphone  
2. **Speech-to-Text** → Converted instantly using Whisper (OpenAI) or Google Gemini  
3. **AI Brain** → The transcribed text is sent to OpenAI GPT-4o / GPT-4-turbo or Google Gemini 1.5 Pro/Flash with a carefully crafted "loving girlfriend" system prompt  
4. **Emotional & playful response** → The model replies in a flirty, caring, supportive, and context-aware way  
5. **Text-to-Speech** → Response is turned back into a beautiful, expressive female voice (OpenAI TTS, ElevenLabs, or browser-native voices)  
6. **She speaks back to you** → Full-duplex, low-latency conversation — feels completely natural

### ✨ Features
- Real-time streaming voice conversation (feels like a phone call with your girlfriend)
- Multiple personality flavors (sweet, teasing, caring, slightly tsundere — easily customizable)
- Remembers conversation history (short-term & optional long-term memory via localStorage or vector DB)
- Emotion-aware responses using prompt engineering
- Switch between OpenAI and Google Gemini models on the fly
- Works 100% in the browser (no server required for basic version)
- Beautiful, minimal UI with animated avatar (optional)
- Fully open-source & self-hostable

### 🛠️ Tech Stack
- **Frontend**: HTML5, JavaScript (Vanilla + Vite/React option)
- **Speech-to-Text**: OpenAI Whisper API or Google Gemini multimodal
- **LLM**: OpenAI GPT-4o / GPT-4-turbo, Google Gemini 1.5 Pro/Flash
- **Text-to-Speech**: OpenAI TTS (`alloy`, `nova`, `shimmer`), ElevenLabs, or Web Speech API
- **Web Audio API** + MediaRecorder for low-latency streaming
