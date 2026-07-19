# Deploying Vanguard Security site to GitHub Pages

Full path to a live GitHub Pages site, using the `index.html` file in this folder. No command line needed — all through GitHub's website.

## 1. Create a GitHub account
Skip if you have one. Go to [github.com](https://github.com) and sign up.

## 2. Create a new repository
Click the **+** (top right) → **New repository**. Name it `vanguard-security`, set it to **Public**, and click **Create repository**. Don't add a README for now.

## 3. Upload your file
On the new empty repo page, click the **uploading an existing file** link (or **Add file → Upload files**). Drag `D:\VanguardSite\index.html` into the box, then scroll down and click **Commit changes**.

## 4. Turn on GitHub Pages
In the repo, go to **Settings** (top menu) → **Pages** (left sidebar). Under **Build and deployment → Source**, choose **Deploy from a branch**. Set the branch to `main` and the folder to `/ (root)`, then click **Save**.

## 5. Get your live link
Wait about 1–2 minutes, then refresh that Pages settings screen. A green banner appears with your live URL:

```
https://<your-username>.github.io/vanguard-security/
```

That's the link you share for the trial. Because the file is named `index.html`, it loads automatically as the homepage.

## Updating it later
Just go to the repo, open `index.html`, click the pencil ✏️ to edit (or upload a new version), and commit — the live site refreshes within a minute or two.

## Heads-up
A public repo means your code is visible to anyone (fine for a static marketing site, but no secrets in there). When you're ready to attach your reserved domain, that's done under the same **Settings → Pages → Custom domain** box, plus a DNS record at your registrar.
