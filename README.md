# Chinese Oral AI Marker

This is a public-deployable version where the Google Speech-to-Text API key is hidden on the server.

## Files

- `index.html` — front-end app
- `api/transcribe-google.js` — serverless backend API
- `package.json` — Vercel setup
- `vercel.json` — Vercel function config

## Deploy on Vercel

1. Create a Vercel account.
2. Create a new project.
3. Upload/import this folder.
4. Add an environment variable:

```text
GOOGLE_SPEECH_API_KEY=your_google_api_key_here
```

5. Deploy.

## Local testing

Install Node.js first, then run:

```bash
npm install
npx vercel dev
```

Open:

```text
http://localhost:3000
```

## Important

Do not put your Google API key inside `index.html`.

For student privacy, avoid recording students saying their full names.
