# Publish Sendora's Privacy Policy Website (Beginner Guide)

This folder contains a complete, ready-to-publish website with Sendora's
Privacy Policy: `index.html` and `style.css`. Follow these steps exactly —
no coding knowledge required. It takes about 5 minutes.

## Step-by-step

**1. Create a GitHub repository**
Go to [github.com/new](https://github.com/new). Enter a repository name,
for example `sendora-privacy`. Leave it set to **Public** (GitHub Pages on a
free account requires the repository to be public). Click **Create
repository**.

**2. Upload files**
On the new repository's page, click **Add file → Upload files**. Drag both
`index.html` and `style.css` from this folder into the browser window (you
do not need to upload this `README.md`). Scroll down and click **Commit
changes**.

**3. Open Settings**
At the top of your repository page, click the **Settings** tab (it's in the
row of tabs near the top: Code, Issues, Pull requests, ... Settings).

**4. Find "Pages" in the sidebar**
On the Settings page, look at the left-hand menu and click **Pages** (under
the "Code and automation" section).

**5. Deploy from a branch**
Under "Build and deployment", find the **Source** dropdown and make sure
**Deploy from a branch** is selected.

**6. Select "main"**
Just below Source, there are two dropdowns. Set the first one (Branch) to
**main**.

**7. Select "/ (root)"**
Set the second dropdown (folder) to **/ (root)**.

**8. Save**
Click the **Save** button next to the dropdowns.

**9. Wait**
GitHub takes about 1–2 minutes to build and publish your site. You can
refresh the Pages settings page to check progress — it will show a message
like "Your site is live at ...".

**10. Copy the generated URL**
Once it's ready, GitHub shows your site's address at the top of the Pages
settings page, in the form:

```
https://YOUR-USERNAME.github.io/sendora-privacy/
```

Copy that URL — this is what you paste into the **Privacy Policy URL** field
in Google Play Console when you set up your app listing.

## Updating the site later

If you ever need to change the Privacy Policy text, edit `index.html` in
this folder, then repeat Step 2 (Upload files) on GitHub with the updated
file — GitHub Pages automatically republishes within a minute or two.
