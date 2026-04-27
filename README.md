# Privacy Policy — 台日地震監測

This repository hosts the privacy policy for the **Taiwan-Japan Earthquake Monitor** iOS app.

本 repo 用於託管「台日地震監測」iOS App 的隱私權政策頁面。

---

## 🌐 Live URL

After enabling GitHub Pages, the policy will be available at:

```
https://<your-username>.github.io/<repo-name>/privacy.html
```

This URL is to be filled in:
- **App Store Connect** → App Privacy → Privacy Policy URL
- **In-app "About" or "Settings" page** (recommended but not required)

---

## 🚀 Deploy to GitHub Pages (3 minutes)

### 1. Create the repo

1. Go to GitHub → **New repository**
2. Name it e.g. `privacy-policy` or `eq-monitor-legal`
3. Set as **Public** (required for free GitHub Pages)
4. Initialize with README

### 2. Upload `privacy.html`

Drag & drop `privacy.html` into the repo root via web UI, or:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# Place privacy.html here
git add privacy.html
git commit -m "Add privacy policy"
git push
```

### 3. Enable GitHub Pages

1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/(root)`
4. Click **Save**
5. Wait ~1 minute, the URL will appear at the top of the Pages settings

### 4. Verify

Open the URL in browser. You should see the styled privacy policy with language toggle.

---

## 📝 Customization Required

Before submitting to App Store, edit `privacy.html` and replace these placeholders:

| Placeholder | Where to Find | What to Replace |
|---|---|---|
| `[請填寫您的聯絡信箱]` | § 08 Contact Us (中文版) | Your support email |
| `[Please fill in your contact email]` | § 08 Contact Us (English) | Your support email |

> Tip: Use `Cmd/Ctrl + F` to find them.

If your bundle ID, AdMob app ID, or third-party services change, update the relevant sections.

---

## 🔄 Updating the Policy

Whenever you change the policy:

1. Edit `privacy.html`
2. Update the `Last Updated` date in the header
3. Commit & push — GitHub Pages will rebuild automatically (~1 min)

---

## 🪪 License

Privacy policy text is provided as-is. Free to adapt for your own apps.
