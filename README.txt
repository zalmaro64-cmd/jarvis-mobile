JARVIS MOBILE 1.0 — Android prototype

This is a small installable-web-app starter, not an APK yet.

To use it on your Android phone:
1. The files must be hosted on an HTTPS website for microphone access and installability.
2. Easiest next step: upload this folder to a static HTTPS host (for example GitHub Pages) using a browser. You can do this from your phone, but the steps are a little fiddly.
3. Open the HTTPS site in Chrome on your Moto G56.
4. Grant microphone permission when asked. Choose English, Arabic, or French.
5. In Chrome's menu, choose "Add to Home screen" or "Install app" if offered.

Current features:
- Three selectable speech-recognition languages.
- Spoken replies using voices available on the phone.
- Typed chat.
- Time/date, basic arithmetic, and Google searches.

Limitations:
noVoice:"La reconnaissance vocale n'est pas prise en charge dans ce navigateur. Vous pouvez écrire.",
- Voice recognition support depends on Android browser support and internet connection.
- The app does not yet connect to a generative AI service.
- It does not listen continuously for "Hey JARVIS".
- Browser restrictions prevent arbitrary phone control or unrestricted app launching.
- Never paste a private AI API key into client-side website code.
