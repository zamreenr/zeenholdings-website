# Zeen Holdings Lanka — Website

## What's in this folder
- `index.html` — Homepage
- `freight-forwarding.html` — Freight forwarding services
- `tea-export.html` — Tea export
- `about.html` — About / company story
- `contact.html` — Contact + quote request form
- `css/style.css` — All styling (colors, fonts, layout)
- `assets/` — Your logo

## Before you go live: activate the contact form
The quote request form on `contact.html` needs a free Web3Forms access key to actually deliver messages to your inbox.

1. Go to https://web3forms.com
2. Enter the email address where you want enquiries delivered
3. Copy the Access Key you're emailed
4. Open `contact.html`, find the line:
   `<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">`
   and replace `YOUR_ACCESS_KEY_HERE` with your real key
5. Save the file

## How to make future edits
Every page is plain HTML/CSS — no build step, no installation needed. Open any `.html` file in a text editor, change the text between tags, save, and re-upload. Claude can also make edits for you any time — just describe the change and share the file.

## Deploying (Phase 3 of your plan)
1. Create a GitHub repository and upload this whole folder
2. In Cloudflare, go to Workers & Pages → create a Pages project → connect it to that repository
3. Deploy — Cloudflare will auto-detect it as a static site (no build command needed)
4. Add your `zeenholdings.com` domain in the Cloudflare Pages custom domains tab
5. Update your nameservers at Namecheap to point to Cloudflare (Claude will give you exact steps when you're ready for this)
