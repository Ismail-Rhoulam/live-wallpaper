# Plash Full-Screen Video Wallpaper

A minimal, full-screen HTML page that plays a looping MP4 video and is designed to be used as a macOS desktop background with **Plash**.

**Note:** The default video used by this project is hosted by a third party and **belongs to its respective owner**. Because the file is not controlled by this repository, it may **change, become unavailable, or disappear at any time**.

---

## Demo / Hosted Version

Once GitHub Pages is enabled, your wallpaper page will be available here:

`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/`

---

## How to Use (Plash on macOS)

1. Enable GitHub Pages for this repo:
   - **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
2. Copy your GitHub Pages URL.
3. Open **Plash**
4. Add a new wallpaper and paste the URL.

Plash will load the page and the video will cover the entire screen.

---

## Customizing the Video

Edit `index.html` and replace the `<source src="...">` URL:

```html
<video autoplay muted loop playsinline>
  <source src="YOUR_VIDEO_URL_HERE.mp4" type="video/mp4" />
</video>
