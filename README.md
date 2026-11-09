# RaptorAI — Privacy Policy & Documentation Page

This directory contains the complete, self-contained **Privacy Policy and Showcase Website** for RaptorAI.

## Official App & Contact Details
* **App Name:** RaptorAI
* **Package ID:** `com.raptorai`
* **Developer / Publisher:** BlueSky Technologies
* **Official Contact:** `blueskytechnologies06@gmail.com`

---

## How to Publish on GitHub Pages (From Any GitHub Account / Repository)

1. **Push the `docs/` folder** to whichever GitHub account and repository you want to host it on:
   ```bash
   git add docs/
   git commit -m "Add Privacy Policy and screenshots"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   * Open the repository on GitHub.
   * Go to **Settings** > **Pages** (in the left sidebar).
   * Under **Build and deployment**:
     * **Source**: `Deploy from a branch`
     * **Branch**: `main` (or your default branch)
     * **Folder**: `/docs`
   * Click **Save**.

3. **Make Sure the Repository is Public**:
   * For standard GitHub accounts, GitHub Pages requires the repository to be **Public** so that Google Play bots and external users can view the page without logging into GitHub.
   * If your main code repository is private, you can simply create a separate, small public repository (e.g. `raptorai-privacy` or `bluesky-policies`), copy the `docs/` contents into it, and enable GitHub Pages there!

---

## URL to Submit in Google Play Console

Once published, your page URL will be:
```text
https://<account-username>.github.io/<repo-name>/
```

In Google Play Console, go to:
**Policy > App content > Privacy policy**
and paste your URL:
```text
https://<account-username>.github.io/<repo-name>/#privacy-policy
```
Google Play Console and Play Store users will be able to access the Privacy Policy directly.
