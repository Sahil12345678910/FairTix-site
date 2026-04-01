# FairTix Website

Interactive 3D landing page for FairTix, a transparent ticketing platform powered by AI & blockchain.

## Quick Start

### Option 1: GitHub Pages (Recommended)
1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Set source to **main branch**, root folder
4. Your site will be live at `https://yourusername.github.io/fairtix-site/`

### Option 2: Open Locally
Just open `index.html` in a browser. Everything loads from CDN, no build step needed.

## Email Collection Setup

The waitlist form redirects to a Google Form pre-filled with the user's email. To set this up:

1. Create a Google Form with one field: "Email Address"
2. Click the three dots menu then Get pre-filled link
3. Enter a placeholder in the email field, click Get link
4. Copy the URL and replace the placeholder URL in `index.html` where it says `GOOGLE_FORM_URL`
5. All emails submitted through the form will appear in your Google Form responses, which you can link to a Google Sheet

## Tech Stack

- Three.js (r128) for 3D hero scene
- React 18 for UI components
- Vanilla CSS with CSS variables
- Zero build tools required

## License

(c) 2026 FairTix. All rights reserved.
