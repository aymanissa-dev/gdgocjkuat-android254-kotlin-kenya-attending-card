# Android254 Kotlin Kenya Meetup — Attending Card Generator

A single-page tool that lets attendees of the **Android254 Kotlin Kenya Meetup Campus Tour** create and download their own personalized "I Am Attending" card — straight from the official event flyer, with their own photo, name, and title added in.

No build tools, no frameworks, no dependencies. Just one `index.html` file, ready to deploy on **GitHub Pages**.

## Features

- 🖼️ Upload a photo — it's automatically fitted and clipped into the card's circular frame
- 🔍 Drag to reposition and use the zoom slider to get the perfect crop
- ✍️ Add your name and title/role — text is centered and auto-sized so it always fits neatly inside the card, never overflowing the borders
- ⬇️ One-click download as a high-resolution PNG, ready to share on social media
- 📱 Fully responsive — works on desktop and mobile browsers
- 🎨 The original event artwork is untouched — this only overlays your details on top of it

## How it works

The card is rendered on an HTML `<canvas>` at the original artwork's full resolution (1254×1254px). The source flyer image is embedded directly in the HTML file, so the whole app is self-contained — there's nothing else to upload or host.

## Deploying on GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Add `index.html` to the root of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
5. Select the branch (usually `main`) and folder `/ (root)`, then save.
6. Your page will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Project structure

```
.
└── index.html   # Everything: markup, styling, and logic in one file
```

## Event details

- **Event:** Android254 Kotlin Kenya Meetup — Campus Tour
- **Host:** Google Developer Group, JKUAT (Jomo Kenyatta University of Agriculture and Technology)
- **Date:** Saturday, 26th September 2026
- **Time:** 9:00 AM – 5:00 PM (EAT)
- **Venue:** IPIC Exhibition Hall, JKUAT Main Campus, Juja

## License

Free to use and adapt for community and event purposes.