# Valerie — donation audit

A web page for auditing photos of donated goods. Claude counts the visible items, matches them to the Goodwill and Salvation Army donation-value guides (or finds cited market prices online), and the page produces an itemized audit as a Word document.

## Using it

1. Open the site.
2. Paste an Anthropic API key (create one at https://platform.claude.com/settings/keys) and press **Check key**.
3. Add up to 6 photos, optional details, and press **Run audit**.
4. Press **Download the Word report**.

Each person uses their own API key. The key stays in their browser and is only sent to `api.anthropic.com`; the page's Content-Security-Policy blocks every other destination. "Remember the key" stores it in that browser only.

## What's in this repository

- `index.html` — the whole site: the auditor instructions, the embedded Goodwill and Salvation Army guides, the valuation arithmetic and the Word-report builder.
- `docx.iife.js` — the docx library (MIT licensed) that builds the Word file in the browser.

Values are approximate references, not a certified appraisal or tax determination. Not affiliated with Goodwill or The Salvation Army.
