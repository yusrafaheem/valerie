# Valerie Donation Audit

Web page for producing a donation audit report (Word document) from photos of donated goods.

Site: https://yusrafaheem.com/valerie/

## Instructions

1. Open the site.
2. Enter an Anthropic API key and select Test key. Keys are created at https://platform.claude.com/settings/keys.
3. Add up to 6 photos. Enter report details if needed.
4. Check the confirmation box and select Run audit.
5. Select Download Word report.

## Notes

- Each user needs their own API key. The key is stored only in the user's browser, and only if "Save key in this browser" is checked. It is sent only to api.anthropic.com.
- Item values are taken from the Goodwill and Salvation Army valuation guides. Items not in the guides are priced from online listings if that option is selected.
- Values are estimates only and are not an appraisal.
- This tool is not affiliated with Goodwill or The Salvation Army.

## Files

- index.html: the web page.
- docx.iife.js: library used to create the Word file (MIT License, see THIRD-PARTY-LICENSES.txt).
