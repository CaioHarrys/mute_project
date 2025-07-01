# 🤟 Tradutor LIBRAS – App Mobile de Acessibilidade

Aplicativo mobile que traduz **sinais da Língua Brasileira de Sinais (LIBRAS)** capturados pela câmera do celular em **texto** e **áudio** em tempo real, facilitando a comunicação entre pessoas surdas/mudas e ouvintes.

---

## 📱 Funcionalidades

- 📷 Captura de sinais com a câmera do celular
- 🧠 Reconhecimento de gestos utilizando IA (MediaPipe + TensorFlow)
- 📝 Conversão de gestos em texto legível
- 🔊 Leitura em voz alta usando TTS (Text-to-Speech)
- ⚙️ Configurações de idioma e voz
- 👥 Inclusão e acessibilidade como foco principal

---

## 🛠️ Tecnologias Utilizadas

### Front-end (Mobile)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [React Navigation](https://reactnavigation.org/)
- [Expo Camera](https://docs.expo.dev/versions/latest/sdk/camera/)
- [expo-speech](https://docs.expo.dev/versions/latest/sdk/speech/)

### IA e Reconhecimento
- [MediaPipe Hands](https://developers.google.com/mediapipe)
- [TensorFlow / Keras](https://www.tensorflow.org/)
- [OpenCV (para pré-processamento)](https://opencv.org/)

### Backend (opcional)
- Python + Flask/FastAPI (servindo o modelo de IA)
- TTS via Google Cloud, Amazon Polly ou ElevenLabs API

---

## 📂 Estrutura do Projeto

'libras-translator-app/
├── mobile/ # App mobile com React Native
│ ├── App.js
│ ├── screens/
│ ├── components/
│ ├── services/
│ └── utils/
├── backend-ia/ # API Python com IA (opcional)
│ ├── main.py
│ ├── models/
│ └── preprocessing/
├── datasets/ # Dataset de sinais LIBRAS
└── README.md'