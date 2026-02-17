# projeto-dio-assistente-virtual-por-voz
Este projeto implementa um assistente de voz utilizando tecnologias gratuitas.

Fluxo do sistema:

- 🎤 O usuário fala pelo microfone
- 📁 O áudio é gravado e salvo
- 📝 O modelo Whisper converte o áudio em texto
- 🤖 Um modelo de linguagem (LLaMA 3 via Groq) gera a resposta
- 🔊 A resposta é convertida em voz com gTTS
- 🎧 O usuário escuta a resposta

O objetivo é demonstrar a integração entre captura de áudio, processamento de linguagem natural e síntese de voz em um único fluxo automatizado.
