# SAMUDRAJ Privacy Website — GitHub Pages Setup

This package contains the SAMUDRAJ Privacy Policy and Account Deletion website using the supplied real transparent logo.

## Files to upload

Upload the **contents** of this extracted folder directly into your GitHub repository root:

- `index.html` — homepage (privacy policy)
- `privacy-policy.html` — direct Privacy Policy URL for Play Console
- `delete-account.html` — public account deletion request page
- `assets/` — logo images used by the HTML pages
- `.nojekyll` — static-site marker
- `README.md` — these instructions

Do not upload the ZIP itself. Do not upload the containing folder as a nested folder. When you open the extracted folder, you should see `index.html` and `assets` right away.

## Step A — Extract

1. Download the ZIP.
2. In Windows File Explorer, right-click it and select **Extract All**.
3. Open the extracted folder. Confirm `index.html`, `privacy-policy.html`, `delete-account.html` and the `assets` folder are visible.

## Step B — Upload to your existing repository

1. Open your repository on `https://github.com/`.
2. Click **Add file → Upload files**.
3. Open the extracted folder on your computer and drag the files `index.html`, `privacy-policy.html`, `delete-account.html`, and `README.md` into the upload area. Drag the entire `assets` folder too so GitHub preserves the folder and its two PNG images.
4. If `.nojekyll` is visible, upload it too. If Windows hides it, this file is optional for this simple static site.
5. Ensure files appear at the repository's top level, with `assets/` as a folder next to them. Do not upload the ZIP or wrap these files inside `samudraj-github-pages-ready/`.
6. Add commit message `Add SAMUDRAJ privacy website` and click **Commit changes** (or **Propose changes**, depending on the GitHub UI).

## Step C — Enable GitHub Pages

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Choose branch `main` and folder `/(root)`, then click **Save**.
4. Open the repository's **Actions** tab and wait for the Pages deployment workflow to finish successfully. In **Settings → Pages**, GitHub will show the published site URL.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Step D — Open the published site (important)

Use the URL shown by GitHub Pages. For a project repository it usually looks like:

- Home: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`
- Privacy Policy: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/privacy-policy.html`
- Account deletion: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/delete-account.html`

Replace both placeholders with your actual GitHub username and exact repository name.

**Do not test page navigation using a GitHub source/code URL** such as `https://github.com/USERNAME/REPOSITORY/blob/main/privacy-policy.html`, and do not use the local file path or downloadable ChatGPT link as the website URL. Source-code pages do not run as your published website. The navigation links are relative and work once all three HTML pages are published in the same directory.

## Step E — Test both directions

Open these two public Pages URLs in a private/incognito window:

1. `.../privacy-policy.html` → click **Account deletion**.
2. `.../delete-account.html` → click **Privacy policy**.

Also open the homepage `.../` and verify the SAMUDRAJ logo displays. A `404` generally means the file wasn't uploaded to the selected publishing source/root, the branch/folder is wrong, the filename's case differs, or deployment has not finished.

Official 404 troubleshooting: https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-404-errors-for-github-pages-sites

## Play Console URLs

After you verify the public URLs, enter:

- Privacy policy: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/privacy-policy.html`
- Account deletion: `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/delete-account.html`

Do not submit placeholders; use the exact published URLs.

## Contact and important compliance checks

- Business/app name: **SAMUDRAJ**
- Privacy/support email: **samudraj.support@gmail.com**
- Monitor this mailbox and respond to requests.
- This external page starts a deletion request by email; it does not automatically delete a Supabase account. You must implement and fulfil deletion requests, and provide an in-app deletion initiation path if users can create accounts.
- Ensure all policy statements match the real app and SDK data practices. This is a starter policy, not legal advice.

Google Play account deletion requirements: https://support.google.com/googleplay/android-developer/answer/13327111
