# Dreem Sabiniano — Portfolio website

Static portfolio built with HTML, CSS, and vanilla JavaScript. No build step or framework required.

## Files
- `index.html` — semantic page structure, metadata, modal, navigation
- `styles.css` — responsive styling, palette, light/dark theme, reduced motion
- `script.js` — rendering, navigation, project dialog, photo edit mode
- `content.js` — all text content, profile links, and image paths
- `images/` — place your own photos and project screenshots here
- `favicon.svg` — simple initial favicon

## Add your images
Replace the placeholder image files listed in `content.js`:
- `images/dreem-portrait.png`
- `images/project-calendar.png`
- `images/project-documents.png`
- `images/project-sourcing.png`
- `images/project-templates.png`

The page displays an image placeholder if a file is missing. Keep the filenames or update the `photos` object in `content.js`.

## Edit photos in the browser
Open your published site and add `#edit` to the URL, for example `https://yourname.github.io/repository/#edit`. Click an image and select a replacement. Choices are saved in that browser's localStorage only; they are not uploaded to GitHub and won't appear for visitors. Use **Reset photos** to clear local changes.

## Resume
Put your PDF at `resume.pdf` in the repository root so the Download Resume link works. Do not add the resume if you do not want it public.

## Publish with GitHub Pages
1. Create a GitHub repository and upload the files/folders in this package to its root.
2. Add your resume as `resume.pdf` if you want the download link to work.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish and open the URL it provides.

Before publishing, replace the placeholder image assets and verify your links and resume file.


## Add actual project links
Each project in `content.js` has a `projectUrl` field. Paste the share link for the actual project there (Google Drive, Google Sheets, a published Notion page, or another public URL). Example: `projectUrl: "https://drive.google.com/drive/folders/YOUR_FOLDER_ID"`. Once populated, that card displays **View Project** and opens the link in a new tab. **Preview Project** always opens the portfolio's built-in preview dialog.

Before publishing, check the sharing permissions for each link in a private/incognito window. Use viewer access only, and do not link confidential employer or client documents. For Google Drive files, make sure the intended audience can view the file.
