# Tummy Timer — privacy policy

The public privacy policy for the **Tummy Timer** Android app, kept here as a
single self-contained page so it can be hosted anywhere without a build step.

`index.html` has no external assets, no scripts and no fonts to fetch. Drop it
on any static host and it works.

## Publishing on GitHub Pages

1. Create a **public** repository — `tummy-timer-privacy` is a sensible name.
   It has to be public: Pages on a private repo needs a paid plan.
2. Upload the contents of this folder to the root of that repo.
3. **Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save.**
4. After a minute the page is live at
   `https://<your-username>.github.io/tummy-timer-privacy/`.

Because the file is called `index.html`, that URL needs no filename on the end.

## Publishing anywhere else

Drag this folder onto [app.netlify.com/drop](https://app.netlify.com/drop), or
use Cloudflare Pages. Both are free and serve static files as-is.

## Before pasting the URL into Play Console

- Open it in a **private browser window**. It has to load with no sign-in —
  Google checks, and a link that prompts for a login is rejected.
- Keep it live. If the URL starts returning 404 after release, Play can pull
  the app.

Then: **Play Console → Policy → App content → Privacy policy → paste the URL.**

## Keeping it accurate

The policy names the app, lists exactly what it stores and states the three
permissions it asks for. If the app ever gains a permission, sends anything off
the device, or adds analytics, this page and the Data safety form both have to
change to match — a policy that disagrees with the Data safety answers is one
of the more common reasons for a review rejection.

A Markdown copy of the same text lives at `../privacy_policy.md` for reference.
Edit both together, or delete that one, so the two cannot drift apart.
