# Voice Claude — Setup Instructions

## What this is
A push-to-talk voice app that talks to Claude AI. Hold the button, speak, release — Claude responds out loud.

---

## How to host it (5 minutes, free)

### Step 1 — GitHub account
If you don't have one: https://github.com/signup (free)

### Step 2 — Create a new repository
1. Go to https://github.com/new
2. Name it: `voice-claude`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload these files
1. Click **uploading an existing file** on the repo page
2. Drag ALL files from this folder into the upload area:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under "Source" select **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Click **Save**
5. Wait ~2 minutes, then your URL will be:
   `https://YOUR-USERNAME.github.io/voice-claude`

---

## Install on Android (Chrome)
1. Open the URL above in Chrome
2. Enter your Anthropic API key when prompted
   - Get one free at https://console.anthropic.com
3. Chrome will show **"Add to Home Screen"** banner, OR tap the 3-dot menu → "Add to Home Screen"
4. Done — it's on your home screen like a real app

## Install on iPhone (Safari)
1. Open the URL in Safari
2. Tap the Share button → "Add to Home Screen"
3. Note: speech recognition may be less reliable on iOS

---

## API Key
- Get it free at https://console.anthropic.com → API Keys → Create Key
- It's stored only on your device (localStorage), never sent anywhere except Anthropic's API
- Pay-as-you-go — costs fractions of a cent per conversation

---

## Usage
- **Hold** the big button → speak
- **Release** → Claude thinks and responds out loud
- Tap **■ stop** to interrupt the response
- Spacebar works too on desktop
