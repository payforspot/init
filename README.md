# payforspot/init

The coming-soon page for **payforspot.co**. One static HTML file, no build.

## Deploy on Render

1. Render dashboard → **New → Blueprint** → select this repo.
2. Accept the plan (one free static site). Done — every push to `main` redeploys.

To hang it on the real domain afterwards: the service's **Settings → Custom
Domains → add `payforspot.co`**, then set the DNS records Render shows you.

## Edit

Everything is in `index.html` — the contact address near the bottom is a
placeholder (`hello@payforspot.co`); change it to a mailbox that exists
before sharing the link. The QR pattern is decorative and not scannable,
on purpose: it becomes a real code when there is somewhere to send people.
