# SynthEx AI

A beautiful AI chat interface powered by Claude.

## Deploy to Netlify

1. Fork/clone this repo
2. Go to [netlify.com](https://netlify.com) → Add new site → Import from Git
3. Select this repository
4. In Site configuration → Environment variables, add:
   - `ANTHROPIC_API_KEY` = your Anthropic API key
5. Deploy!

## Features

- Multi-model support (Opus 4.6, Sonnet 4.6, Sonnet 4.5, Haiku 4.5)
- Streaming responses with stop button
- File uploads (drag & drop, click, or paste images)
- Web search integration
- Extended thinking mode
- File generation with View/Download
- Text-to-speech
- Regenerate with version history
- Search conversations
- Edit/delete conversations
- External link safety dialog
- Mobile responsive
- Dark theme with SynthEx branding

## Local Development

Just open `index.html` in a browser. Note: API calls require the Netlify function proxy.
