# T-C-Analyzer-v1.1

A free, browser-based tool that uses AI to analyze Terms & Conditions documents and tells you in plain English whether you should agree, proceed with caution, or decline.

No backend. No server. Just open the HTML file and go.

---


## Features

- **Paste or URL** — paste T&C text directly or enter a URL to fetch it automatically
- **AI verdict** — get a clear recommendation: ✅ Agree, ⚠️ Caution, or ❌ Decline
- **Scores** — privacy, fairness, transparency, and user rights rated 0–100
- **Flags** — red, amber, and green flags highlighting key clauses
- **Key points** — plain-English breakdown of data usage, cancellation, liability, and content ownership
- **TL;DR** — one sentence summary of the entire document
- **History** — past analyses saved in your browser so you can revisit them anytime
- **Your key, your browser** — API key is stored locally and never exposed in code

---

## How to Use

1. **Download or clone this repo**
   ```bash
   git clone https://github.com/UkaohaCC/T-C-Analyzer-v1.1.git
   ```

2. **Open `index.html` in your browser**
   - No install needed. No terminal. Just double-click the file.

3. **Get a free Gemini API key**
   - Go to [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
   - Sign in with a Google account
   - Click **Create API key** and copy it

4. **Enter your key in the app**
   - Paste it into the API Key field at the top
   - Click **Save** — it's stored in your browser only, never in the code

5. **Analyze any T&C**
   - Paste the terms text, or enter the URL of the T&C page
   - Click **Analyze** and wait a few seconds
   - Read your results!

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript |
| AI | Google Gemini API (`gemini-3.1-flash`) |
| Storage | Browser localStorage |

No frameworks. No build tools. No dependencies.

---

## Limitations

- **URL fetching** uses a public CORS proxy (`corsproxy.io`) — some sites may block it
- **Free API tier** allows 15 requests/minute and 1,500/day (more than enough for personal use)
- **Long documents** are trimmed to 8,000 characters before being sent to the AI

---

## License

MIT License — free to use, modify, and share.

---

Built by Me using HTML, CSS, JavaScript, and the Google Gemini API. 9TH JUNE, 2026.
