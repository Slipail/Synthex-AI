# SynthEx AI

AI chat interface deployed on Cloudflare Pages.

## Deploy to Cloudflare Pages

1. Push this repo to GitHub
2. Go to [dash.cloudflare.com](https://dash.cloudflare.com) → Workers & Pages → Create
3. Connect your GitHub repo
4. Build settings: Leave blank (static site + functions)
5. Add environment variable: `ANTHROPIC_API_KEY` = your key
6. Deploy!

The `functions/api/chat.js` file automatically becomes the `/api/chat` endpoint.

## Features

- Multi-model support (Core 4.6, Pulse 4.6, Pulse 4.5, Spark 4.5)
- Google Sign-In authentication
- Cloud sync via Firebase Firestore
- Usage limits (25 messages per 3 hours per model)
- Streaming responses
- File generation with View/Download
- Image lightbox viewer
- External link safety dialog
- Mobile responsive
- Dark theme
