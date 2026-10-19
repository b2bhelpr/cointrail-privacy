# CoinTrail — Legal & Privacy (public policy site)

This repository hosts the **public Privacy Policy, Terms of Service, and Disclaimer** for the CoinTrail Android app, served via GitHub Pages.

**Live page:** `https://b2bhelpr.github.io/cointrail-privacy/`

This URL is what gets pasted into the Google Play Console (app privacy form, Data safety, and the Google Cloud OAuth consent screen).

## Sync rule

The source of truth for this text is `lib/screens/legal_screen.dart` in the private app repository (`rajamut/cointrail`). If wording ever changes, apply it in **both** places, bump the "Last Updated" date in both, and update the `test/p_privacy_statement_test.dart` assertions. The last content review (batches ⑩ + ⑪ of the code audit) verified every statement against actual app behavior.

## Enable GitHub Pages

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**
3. The site goes live at the URL above within a minute or two.
