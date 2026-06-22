# Nash V5.1 — Multi-Subject Smart Tutor

Subjects:
- Entrepreneurship & Innovation (EAI 1200)
- Spanish A1 / ELE

V5.1 features:
- Multi-subject homepage
- Subject-aware dashboard
- Smart tutor context sent to Netlify Function
- Explain-my-mistake practice
- Infinite practice cases for both subjects
- Flashcards and memory tricks

Netlify setup:
1. Deploy through GitHub so `netlify/functions/tutor.js` is detected.
2. Add environment variable `OPENROUTER_API_KEY`.
3. Redeploy.
4. Test `/.netlify/functions/tutor`.
