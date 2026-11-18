PULL UP ON NETLIFY

Deploy in 1 minute:
1. Go to app.netlify.com/drop
2. Drag this whole folder (or the zip) onto the page
3. Netlify gives you a link like pull-up-123.netlify.app. Rename it in Site settings, or add your own domain.

How it works on Netlify:
- This is the Pull Up prototype as a static site. It runs in "demo mode": sample events load, and every change
  (events you create or edit, tickets, profiles, settings) saves in that visitor's own browser.
- Data is NOT shared between people yet. Each phone sees its own copy. To share data, connect the backend in
  pullup-backend.zip (Supabase + Stripe) and point the app at its API.
- Checkout, payouts and plans are fake in demo mode. No card is charged.
- "Write it for me" uses a built in template here instead of AI.
- On iPhone, open the link in Safari, tap Share, then Add to Home Screen to install it like an app.
- Me > Reset sample data starts fresh.

Files:
index.html            the whole app
netlify.toml          security headers and caching
manifest.webmanifest  lets people add it to their home screen
icon.svg              app icon
