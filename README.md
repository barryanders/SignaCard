<h1>SignaCard</h1>

**SignaCard is a free, local-first email signature card builder for creating polished HTML email signatures that feel more like business cards than generic footers.** It runs as a standalone web app, stores your signature settings locally in your browser, and gives you copy-ready signature HTML for email clients that accept formatted paste.

<p>
  <a href="https://barryanders.github.io/SignaCard/">
    <img alt="Open SignaCard" src="https://img.shields.io/badge/Open-SignaCard-111827?style=for-the-badge">
  </a>
  <a href="https://github.com/barryanders/SignaCard">
    <img alt="Code on GitHub" src="https://img.shields.io/badge/Code-GitHub-f4c763?style=for-the-badge&logo=github&logoColor=111827&labelColor=f4c763&color=f4c763">
  </a>
</p>

## Email Signature Card Builder

SignaCard helps you design reusable email signatures with a card-based look. It is built for people who want something more distinctive than a plain name/title footer, while still keeping the generated HTML practical for Gmail, Outlook, Apple Mail, and other email clients.

Use SignaCard to build signatures for:

- executives and founders
- sales and customer success teams
- support and help desk teams
- HR, recruiting, and people operations
- lawyers and consultants
- doctors, clinics, and care providers
- schools, professors, students, and departments
- real estate agents and property managers
- finance, insurance, and accounting professionals
- creators, writers, designers, and media teams
- nonprofits, churches, and community programs
- hospitality, events, restaurants, and travel
- contractors, trades, and field service teams
- themed signatures such as medieval, space opera, wizard academy, library card, film noir, and retro terminal styles

## Privacy-First Local Storage

SignaCard stores your signature settings in your own browser on your own computer. Your name, title, contact information, photo URL, logo URL, colors, and saved choices are not uploaded to a SignaCard cloud account.

Because browser storage is local, download backup copies of important signatures. Backups make it easy to restore your setup later or move it to another browser.

## Features

- 100 premade email signature card designs
- 18 searchable design categories
- Search and category filtering
- Editable name, title, company, photo URL, logo/text, email, phone, website, location, and tagline
- Accent color customization
- Photo shape controls
- Locked light, locked dark, or email-client-controlled color behavior
- Table-based inline HTML output for email-client compatibility
- Copy formatted signature for email clients that accept rich paste
- Copy raw HTML
- JSON export and import for local backups
- Single standalone HTML file
- No account
- No subscription
- No analytics
- No ads
- No tracking
- No cloud signature library

## How It Works

1. Open the app in your browser.
2. Pick a signature card design.
3. Edit your contact details, image URLs, colors, and photo shape.
4. Choose whether the signature should keep locked colors or allow email-client color behavior.
5. Copy the formatted signature or copy the raw HTML.
6. Paste it into your email client's signature settings.
7. Send yourself a test email before using it widely.

Email clients handle signature HTML differently. SignaCard uses table-based inline HTML and standard fonts, but Gmail, Outlook, Apple Mail, mobile clients, and corporate email systems may still adjust spacing, images, links, or dark-mode behavior.

## Run Locally

No build step is required.

```bash
python3 -m http.server 4174
```

Then open:

```text
http://localhost:4174/
```

You can also open `index.html` directly in a browser.

## Image Notes

SignaCard lets users provide remote image URLs for a profile photo or logo. This is more reliable than embedding decorative images directly in the generated signature because many email clients block images, strip data URLs, or alter image rendering in dark mode.

For best results, use HTTPS image URLs and test the signature in your actual email client before sending.

## Why SignaCard Exists

Most email signature generators produce the same few corporate layouts. SignaCard focuses on distinctive card-style signatures: professional enough for real work, flexible enough for different industries, and local-first so your contact details and drafts stay in your browser.

## Say Thanks

SignaCard is free. If it helped you, feel free to [buy me a coffee](https://buymeacoffee.com/barryanders) as a thank you.

## Author

<a href="https://barryanders.github.io" rel="nofollow">
  <img alt="Barry Anders" src="https://avatars.githubusercontent.com/u/91902180?v=4&amp;s=200" style="max-width: 100%;border-radius:50%;" width="100" height="100">
  <br>
  <strong>Barry Anders</strong>
</a>

## License

MIT
