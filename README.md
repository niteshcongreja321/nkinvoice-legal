# NK Invoice Legal Pages

Public privacy policy and terms of service for the NK Invoice iOS app.

Live site: https://niteshcongreja321.github.io/nkinvoice-legal/

Support email: nkinvoice@gmail.com

Last updated: 28 September 2026

## What the pages cover

- **Privacy Policy:** the app works without an account (data stays on the
  device); optional Sign in with Apple or Google to back up and sync through
  Supabase (AWS Seoul, ap-northeast-2); NK Invoice Pro subscriptions sold by
  Apple, with status managed by RevenueCat; local notifications, Face ID /
  passcode lock, and on-device CSV/PDF export; no ads, analytics, or tracking;
  retention, deletion, and user rights.
- **Terms of Service:** optional accounts, the free plan and NK Invoice Pro,
  auto-renewing subscription terms (billing, renewal, free trial, cancellation,
  refunds via Apple), and Apple's standard EULA.
- **Support:** contact email and answers to common questions (accounts,
  moving devices, the free plan, restore, cancel, export, delete account).

## Pages

| Path | URL |
|------|-----|
| Privacy Policy | https://niteshcongreja321.github.io/nkinvoice-legal/privacy-policy/ |
| Terms of Service | https://niteshcongreja321.github.io/nkinvoice-legal/terms/ |
| Support | https://niteshcongreja321.github.io/nkinvoice-legal/support/ |

## GitHub Pages setup

1. Create a public GitHub repository named `nkinvoice-legal` under your account
   (`niteshcongreja321/nkinvoice-legal`).

2. Push this directory to the repository:

   ```bash
   cd /path/to/nkinvoice-legal
   git init
   git add .
   git commit -m "Add NK Invoice legal pages"
   git branch -M main
   git remote add origin https://github.com/niteshcongreja321/nkinvoice-legal.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Open the repository on GitHub.
   - Go to **Settings** → **Pages**.
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**.
   - Choose branch `main` and folder `/ (root)`.
   - Save.

4. Wait a minute or two, then verify:
   - https://niteshcongreja321.github.io/nkinvoice-legal/
   - https://niteshcongreja321.github.io/nkinvoice-legal/privacy-policy/
   - https://niteshcongreja321.github.io/nkinvoice-legal/terms/
   - https://niteshcongreja321.github.io/nkinvoice-legal/support/

## Updating pages

Edit the HTML files in this repo, commit, and push to `main`. GitHub Pages will
publish the updated content automatically.

## App Store / Play Store links

Use these URLs in App Store Connect and Google Play Console:

- **Privacy Policy URL:** `https://niteshcongreja321.github.io/nkinvoice-legal/privacy-policy/`
- **Support URL:** `https://niteshcongreja321.github.io/nkinvoice-legal/support/`
- **Terms of Use URL:** `https://niteshcongreja321.github.io/nkinvoice-legal/terms/`
  (needed because the app sells auto-renewing subscriptions)

## Local preview

Open any HTML file in a browser, or serve the folder locally:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080/privacy-policy/
## Supabase keep-alive

`.github/workflows/supabase-keepalive.yml` pings the NK Invoice backend
(Supabase project `ydjswmzjqlvxurgtjwni`) once a day at 07:23 UTC, so the free
project doesn't pause. It lives here because Actions is free for public repos.
It uses only the app's public anon key. A failed run means the project may be
paused: restore it in the Supabase dashboard.
