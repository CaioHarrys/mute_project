# 🤟 Tradutor de LIBRAS – Comunicação Inclusiva em Tempo Real

Este é um aplicativo mobile criado para facilitar a **comunicação entre pessoas surdas/mudas e ouvintes**, traduzindo sinais em **LIBRAS (Língua Brasileira de Sinais)** em **texto e áudio em tempo real**, usando a câmera do dispositivo, visão computacional e inteligência artificial.

---

## 📱 Funcionalidades

- 📸 Captura de sinais com a câmera do celular
- ✋ Reconhecimento de gestos em LIBRAS (letras, palavras e frases)
- 🧠 Conversão dos sinais em texto usando IA treinada
- 🔊 Transformação do texto em fala (TTS) para comunicação com ouvintes
- ⚙️ Configurações de voz, idioma e velocidade da fala
- 🔒 Interface acessível, leve e otimizada para dispositivos móveis

---

## 🧠 Arquitetura do Projeto

```text
Usuário faz sinal com a mão
        ↓
Camera do celular com MediaPipe Hands
        ↓
Detecta posição e movimento dos dedos
        ↓
Modelo de IA interpreta o gesto → Palavra
        ↓
Palavra aparece como TEXTO na tela
        ↓
Text-to-Speech (TTS) converte para áudio
        ↓
Áudio é reproduzido para pessoa ouvinte

