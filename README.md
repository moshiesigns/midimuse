# MIDIForge

Landing page for MIDIForge — a MIDI library and AI music creation platform for DJs and producers.

React, TypeScript, Tailwind CSS, and Vite. Frontend prototype only. MIDI downloads, AI generate, and SoundCloud/Spotify controls are mock UI and are not live.

## Run locally

```bash
npm install
npm run dev
```

## Deploy

Push this folder to your own GitHub, then import the repo on [Vercel](https://vercel.com) (or Netlify). Use the default Vite build: `npm run build`, output `dist`.

## Waitlist

Signups go through FormSubmit to the email in `src/components/Waitlist.tsx` (`SIGNUP_INBOX`). Change that address if you want them somewhere else. The first submission to a new inbox needs a one-time activation click in that email.
