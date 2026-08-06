# Fed & Watered — standalone app

Your household recipe app: library, weekly planner, combined shopping list,
cook mode, rankings, "Ask the dogs" and cookbook scanning. Runs entirely in
the browser — no Claude account needed to use it.

## Put it online with GitHub Pages (free, ~5 minutes)

1. Sign in at github.com (create a free account if needed).
2. Click **+** (top right) → **New repository**. Name it `fed-and-watered`,
   leave it **Public**, tick **Add a README**, click **Create repository**.
3. In the repo, click **Add file → Upload files**, drag ALL the files from
   this folder in (index.html, app.js, sw.js, manifest.json, both icons),
   then **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch", choose `main` and `/ (root)`,
   click **Save**.
5. Wait a minute, refresh, and GitHub shows your link:
   `https://YOURNAME.github.io/fed-and-watered/`

## Install it on your phones

Open the link, then:
- **iPhone (Safari):** share icon → **Add to Home Screen**
- **Android (Chrome):** ⋮ menu → **Add to Home screen**

It opens full-screen with its own icon, and works offline once loaded.

## Things worth knowing

- **Data lives on each device** (in that browser's storage). You and your
  partner each have your own library. Use **⚙ Settings → Export backup** to
  copy a library from one phone to another, and export occasionally as a
  backup — clearing Safari/Chrome website data would wipe the app's data.
- **Cookbook scanner:** needs an Anthropic API key (console.anthropic.com →
  API keys). Paste it in **⚙ Settings** on each device. It's stored only on
  the device, never in this code. Scans cost a fraction of a penny each.
  Everything else works without a key.
- **Updating the app:** replace the files in the GitHub repo with new
  versions and the site updates itself.
