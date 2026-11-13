# Hi, I'm Halil 👋

I build **AI automation** and **Android apps**, from the first prototype to Google Play.
Based in Belgium (CET). Website: [asya-aa.com](https://asya-aa.com)

- **Automation:** Python services that read emails, PDFs and scans and put the data where it belongs
- **AI integration:** Gemini and Claude with fallbacks, grounded answers, safety layers, structured output
- **Mobile:** Flutter and native Kotlin (Jetpack Compose), Firebase backends in Node.js / TypeScript
- **Ops:** 12 years of Linux server administration, CI/CD with GitHub Actions

Most of my code is private because it runs real products and client systems. Below is what each project does.

---

## 📱 Apps on Google Play

### Lernio: Study Coach & Screen Time · [Google Play](https://play.google.com/store/apps/details?id=com.lernio.app)
An Android app with two roles, Parent and Student. Instead of banning the phone, the child earns free time by focusing on schoolwork.
AI study coach (text and voice) that guides instead of giving answers, AI quizzes from official curricula in 25 countries, and parental controls (remote lock, app blocking, daily limits, uninstall protection).
`Flutter` `Kotlin` `Firebase (EU)` `Gemini / Vertex AI` `Claude` `RevenueCat` · 13 languages

### PDF Editor: Text & Signature · [Google Play](https://play.google.com/store/apps/details?id=com.asya.pdfeditor)
A full PDF editor that runs entirely on the device: edit text in the original font, OCR for scanned pages, forms, signatures, merge/split, AES-256 protection.
About 13,500 lines of Kotlin with unit and emulator UI tests in CI.
`Kotlin` `Jetpack Compose` `PdfBox` `ML Kit OCR` `Play Billing` · 12 languages

## 🧪 Apps in closed testing

### VoiceDump
Speak for 30 seconds and AI turns it into tasks, shopping lists, appointments and notes with real dates. Change them by voice ("move the dentist to Friday"). Reminders, alarms, shared lists, home-screen widgets.
`Flutter` `TypeScript Cloud Functions` `Kotlin widgets` `Speech-to-Text` `Gemini` `Claude`

### HerbMind
AI plant assistant (text, voice or photo) grounded on a curated knowledge base of 150 plants in 10 languages, with a safety layer on both the question and the answer.
`Flutter` `Node.js Cloud Functions` `Gemini` `RevenueCat` `GitHub Actions + Cloud Build`

## ⚙️ Automation and platforms

### Asya Sync (in production)
A Python service for transport companies in Belgium: reads order emails and their attachments, extracts the data and enters it into the transport management system. Duplicate checks, retries and a log of every step. Runs every day.
`Python` `OCR` `LLM extraction` `REST APIs`

### ASYA Fleet
Fleet tracking and tachograph platform for hauliers.
`JavaScript`

### AI social media promo pipeline (built and tested)
Turns a product into platform-specific posts (Claude) and a short vertical video (Google Veo + ffmpeg). Human approval before anything is posted; dry run by default.
`Node.js` `Anthropic API` `Google Veo` `ffmpeg` `GitHub Actions`

---

💬 Need something automated or an app built? Find me on Upwork or at [asya-aa.com](https://asya-aa.com).
