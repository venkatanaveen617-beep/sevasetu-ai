# SevaSetu AI — Voice Form Assistant (Prototype)

A beginner-friendly, bilingual (Telugu + English) browser prototype that guides a user through a sample form using speech and editable fields.

## Features
- Telugu and English interface/questions
- Browser speech recognition (where supported) and text-to-speech
- Guided question-by-question form filling
- General, college, and public-service enquiry sample forms
- Edit fields, review missing values, read form aloud, download `.txt`
- No backend, no account, and no application submission

## Run it
1. Extract this ZIP.
2. Open `index.html` in Chrome or Edge.
3. Press **Start voice assistant**.
4. Allow microphone access if requested.
5. Choose Telugu or English, press **Speak answer**, and answer each question.

If microphone recognition does not work from a local file, use VS Code Live Server or publish with GitHub Pages. Browser speech recognition support varies; typing answers is always available.

## Publish with GitHub Pages
1. Create a GitHub repository named `sevasetu-ai`.
2. Upload `index.html` and this `README.md`.
3. Open the repository **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the published Pages URL to appear.

## Important limitations
- This is a demo, not an official government service.
- It does not submit forms or connect to government databases.
- Sample questions are not official eligibility/document requirements.
- Speech recognition may send audio to your browser vendor's speech service depending on browser settings. Do not enter sensitive data in this demo.
- Before using real forms, add verified official sources, strong privacy/security protections, and a clear user-confirmation step.
