# Rohin Krishnan GitHub Pages site

## Files
- `index.html`
- `styles.css`
- `profile.png` ← put your CLEAN transparent-background photo here

## Setup

1. Rename your cleaned transparent PNG to exactly:

   `profile.png`

2. Put it in the same folder as `index.html`.

3. In `index.html`, replace:
   - `YOUR_EMAIL_HERE`
   - `YOUR_GITHUB_USERNAME`
   - `YOUR_CV_LINK_HERE`

4. Upload all files to the root of your GitHub Pages repository.

5. Commit the changes.

## Important

The CSS intentionally applies:
- no opacity
- no blur
- no CSS filters
- no shadow
- no overlay
- no masking
- no blend mode

So if `profile.png` itself is clean, the website will display it cleanly too.

If GitHub Pages still shows the previous photo, hard-refresh the site:
- macOS Firefox/Chrome: `Cmd + Shift + R`

You can also rename the image to something new, such as `profile-v2.png`, and update the `src` in `index.html` to force GitHub/browser cache invalidation.
