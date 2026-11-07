# AMAI AI Studio — Ultimate Edition starter

A responsive, single-page AI workspace using the official Puter.js browser SDK.

## Included
- AI chat with selectable model IDs
- AI image generation
- AI writing assistant
- Code assistant
- Image analysis from a selected local image
- Prompt library
- Local browser history
- Responsive dark interface

## Run / publish
1. Keep `index.html` at the root of your hosting project.
2. Publish the folder with GitHub Pages, Netlify, or another static HTTPS host.
3. Open the HTTPS URL and test each module.
4. To embed in Blogger, use the provided `blogger-embed.html` snippet and replace `YOUR-HOSTED-APP-URL` with the actual published URL.

Puter.js is loaded from `https://js.puter.com/v2/`. Users may be prompted to sign in to Puter. Model availability and user costs/limits are controlled by Puter's current service and terms; check the official docs before production use.

## Important
- This is a front-end starter, not a production backend or a guarantee of unlimited/free AI usage.
- Do not put private API keys, passwords, or secrets in this public client-side project.
- AI usage, authentication, cookies, and popup behavior inside Blogger iframes may be limited by browser policies. If sign-in does not work inside the embed, use the full-screen hosted app link.
- Local history is stored in the current browser only and can be erased by clearing browser data.
- Test all features on your target devices before sharing publicly.

## Official docs
- https://docs.puter.com/getting-started/
- https://docs.puter.com/AI/
- https://docs.puter.com/AI/chat/
- https://docs.puter.com/AI/txt2img/
