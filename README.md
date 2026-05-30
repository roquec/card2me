# card2me 🪪

Create a digital contact card in seconds — just a shareable link, no sign-up, no server.

**card2me** is a single-page, fully static website that lets anyone build a slick digital
contact card and share it as a link. The card's data is encoded directly into the URL,
so every card is just a shareable hyperlink you can drop into a chat, email, or QR code.

## Features

- Simple form to enter name, title, company, phone, email, website, address, note and an optional photo.
- Generates a unique shareable URL containing the card data, no backend required.
- "Add to Contacts" button downloads a standard `.vcf` (vCard 3.0) file, including the embedded photo.
- One-click "Copy link" to share the card anywhere.
- Clean, playful, responsive dark UI.

## Usage

Just open `index.html` in a browser — or host it on any static file host
(GitHub Pages, Netlify, Vercel, S3, etc.).

1. Fill in the form and hit **Create card**.
2. You'll be redirected to your card's shareable URL.
3. Send that link to anyone — they can view the card and add you to their contacts.

## Tech

Plain HTML, CSS and vanilla JavaScript. No build step, no dependencies.

## License

See [LICENSE](LICENSE).
