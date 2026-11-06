# Happy Birthday Deepak Yadav 🎂

A responsive birthday website with a photo gallery, confetti, candle interaction, birthday wishes form, and WhatsApp sharing.

## Folder structure

```text
Deepak-Birthday-Website/
├── index.html
├── README.md
├── .nojekyll
└── assets/
    └── images/
        ├── memory-01.jpg
        ├── memory-02.jpg
        └── ... memory-20.jpg
```

## Deploy with GitHub Pages

1. Sign in to GitHub and create a **new public repository** (for example, `deepak-birthday`).
2. Open the repository and choose **Add file → Upload files**.
3. Upload the **contents of this folder** (`index.html`, `README.md`, `.nojekyll`, and the `assets` folder). Do not upload only the ZIP file.
4. Click **Commit changes**.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then click **Save**.
8. Wait a minute or two. GitHub will show your website address in the Pages section.

## Deploy with Vercel

1. Push this folder's contents to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Keep the framework preset as **Other**. Leave the build command and output directory empty/default.
4. Click **Deploy**. The `index.html` file is the website entry point.

## Important note about birthday wishes

This is a static website, so wishes are saved in the visitor's own browser only. They are not automatically shared with other visitors or stored in a central database. Use the **Share on WhatsApp** button to send a wish to Deepak. A shared live wishes wall would require a separately configured backend/database.

## Local preview

Open `index.html` in a modern browser. An internet connection is needed for the Google Fonts; the rest of the page and gallery are included in this folder.
