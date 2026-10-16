# Dukaan Helper 🛍️

Turns a shopkeeper's product details (Hindi / Hinglish / English) into a ready-to-send WhatsApp catalog message, online listing, or Instagram caption.

**Open-source AI at the core:** runs Google's open-weight **Gemma** model locally through **Ollama**. No API key, no cost per listing, and shop data never leaves the laptop.

## Run it
1. Install Ollama: https://ollama.com/download
2. `ollama pull gemma3:1b`
3. Allow the page to talk to Ollama:
   - Mac/Linux: `OLLAMA_ORIGINS="*" ollama serve`
   - Windows (PowerShell): `$env:OLLAMA_ORIGINS="*"; ollama serve`
4. Open `index.html` in Chrome. Type product details, click **Write my listing**.

Bigger model = better Hindi: `ollama pull gemma3:4b` and change the model name in Settings.

Built with HTML/CSS/JS. Built during Hacktoberfest Open-Source AI Challenge: Week 2 (Oct 12-18, 2026).
