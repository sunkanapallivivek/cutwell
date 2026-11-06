# Cutwell

Cutwell is a free, browser-only video clip editor. It does not need a server,
account, paid hosting, Python, or FFmpeg. Videos are processed locally in the
browser and are not uploaded by the editor.

## Publish for free with GitHub Pages

1. Create a **public** GitHub repository named `cutwell`.
2. Upload `index.html`, this `README.md`, and the `.github/workflows/deploy-pages.yml`
   file to the repository's `main` branch.
3. In the repository, open **Settings → Pages** and set the build source to
   **GitHub Actions**.
4. Open the **Actions** tab and wait for **Deploy Cutwell to GitHub Pages** to
   finish. The public website URL will be shown in the workflow deployment
   details and under **Settings → Pages**.

The GitHub repository must be public for GitHub Pages on a free plan. Anyone
can view its files and use the website. Do not upload private videos or secrets
to the repository; the editor does not upload users' selected videos.

Open `index.html` in a current version of Edge or Chrome and choose a video.
For automatic clipping, choose the number of clips and select **Find moments**.
Review each proposed segment with its **Preview** button, then use **Select** or
**Selected** to choose which moments to export. No clips are encoded until you
click **Export**. For a manual clip, set the range and click **Export selected
clip**. The browser must support the selected MediaRecorder format; available
formats are listed in the editor.

Encoding happens in real time, so each clip may take about as long to export as
its selected duration. Automatic multi-clip export processes clips one at a
time after the user confirms export. Keep the tab open while exporting. Browser
memory, video codecs, and device performance limit which files can be processed.

Only edit footage you own or are authorized to use. Cutwell does not remove
copyright or grant usage rights.
