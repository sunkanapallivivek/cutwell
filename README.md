# Cutwell

Cutwell is a free, browser-only video clip editor. It does not need a server,
account, paid hosting, Python, or FFmpeg. Videos are processed locally in the
browser and are not uploaded by the editor.

## Open Cutwell

[Open Cutwell](https://sunkanapallivivek.github.io/cutwell/) — use the HTTPS
address. The site is published with GitHub Pages.

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
