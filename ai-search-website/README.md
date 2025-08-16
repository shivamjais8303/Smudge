# AI Search Website (Vercel)

A minimal AI search UI with a secure Vercel Function that calls OpenAI.

## Deploy
1. Push this repo to GitHub.
2. On Vercel, import the repo and set env var `OPENAI_API_KEY`.
3. Deploy. Visit your site and ask away.

## Local Dev (optional)
- Install the Vercel CLI: `npm i -g vercel`
- Run: `vercel dev`

## Config
- Model: `gpt-4o-mini` (change in `api/ask.js`)
- Endpoint: `/api/ask`

## Notes
- Never expose your API key on the frontend.
- For streaming responses, upgrade the function to stream and use `ReadableStream` in the browser.
