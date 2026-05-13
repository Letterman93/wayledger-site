# Wayledger Site

Public landing website for Wayledger at getwayledger.com.

## What belongs here

- Landing page
- Public marketing copy
- Public brand and image assets
- Waitlist/contact form
- GitHub Pages configuration

## What does not belong here

- App dashboard source
- Backend/API code
- Personal finance data
- Secrets or API keys

## Preview

You may view this website by going to www.getwayledger.com in a browser. For local preview, open index.html directly in a browser, or serve this folder with any static file server.

## Deploy

This repo is intended for GitHub Pages. The included workflow publishes the repository root as a static site. The CNAME file points GitHub Pages to getwayledger.com.

## Form Handling

GitHub Pages is static hosting, so the waitlist form needs a hosted form endpoint before public launch. Use a service such as Formspree, Google Forms, or a small backend endpoint when the app backend is ready.

Do not expose private email credentials or API keys in this repository. A branded contact address or email forwarder can be used later, but form submissions should still go through a proper form handler.
