# LLM-Powered-Language-Translation-System
A multilingual language translation system powered by Google Gemini 1.5 Flash and LangChain. It auto-detects source language, translates to target languages, and provides detailed explanations, all through an interactive Gradio interface for an engaging user experience.

# 🌍✨ LLM-Powered Multilingual Translator

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square)
![Gradio](https://img.shields.io/badge/Gradio-UI-lightgrey?style=flat-square)
![LLM](https://img.shields.io/badge/Powered%20by-Gemini%201.5%20Flash-orange?style=flat-square)

An intuitive and smart translation tool powered by **Gemini 1.5 Flash**, designed for global language understanding. It features automatic language detection, multilingual translation, and contextual explanations — all wrapped in a clean Gradio interface.

---

## 🚀 Features

- 🔍 **Auto Language Detection** — no need to select the source language
- 🌐 **Multilingual Translation** — supports 🇮🇩 Indonesian, 🇬🇧 English, 🇯🇵 Japanese, 🇸🇦 Arabic, 🇫🇷 French, 🇪🇸 Spanish, 🇩🇪 German, and more
- 🧠 **Contextual Explanation** — gives gender-aware and culturally nuanced translations (e.g. Arabic)
- 🎛️ **Modern UI** — powered by Gradio with flexible dropdown + manual input
- 🧩 **Easy to Extend** — ready for integration with other LLMs or APIs

---

## 🖼️ Interface Preview

> 📌 *If you're on Colab, you can try the app live!*

![Translator UI](https://via.placeholder.com/1000x400.png?text=Gradio+Interface+Preview)

---

## 🧪 Example Output

> **Input:** `aku suka dirinya`  
> **Target Language:** Arabic  
>
> **📝 Translated Sentence:** أنا أحبّهُ *(for male)* / أنا أحبّها *(for female)*  
> **📘 Explanation:** This means "I like him/her", depending on gender. In Arabic, gender-specific verbs are used.

---
🧠 Tech Stack
Tool	Purpose
🧠 Gemini 1.5 Flash	LLM for translation and reasoning
🐍 Python	Backend logic
🎛️ Gradio	Web interface frontend
🔤 Langdetect	Automatic source language detection

🔮 Roadmap
 Add speech input & audio output

 Add sentence alignment for learning use-cases

 Connect to HuggingFace-hosted LLMs

 Integrate FAISS vector search for memory-based translation

🤝 Contributing
Contributions, suggestions, and pull requests are welcome!
Feel free to fork this repo or open issues.
