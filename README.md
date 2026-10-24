# Image Upload & Custom Link (GitHub Pages)

## One-time setup
1. Create a free account at https://cloudinary.com/
2. Find your **Cloud name** in the Cloudinary Console.
3. Open **Settings → Upload → Upload presets → Add upload preset**.
4. Set **Signing Mode** to **Unsigned**, save, and copy the preset name.
5. Upload `index.html` to the root of a public GitHub repository and enable **Settings → Pages → Deploy from a branch → main → /(root)**.
6. Open the published site and enter cloud name and preset name. Click **Setup save karein**. These are saved only in that browser.

## Use
Enter a name, select an image, and click **Image upload karke link banayein**. The site provides the direct image URL and a shareable page link.

## Notes
GitHub Pages is static and cannot store uploaded files itself. Cloudinary stores images. Configure restrictions on your unsigned preset (allowed formats and maximum file size); never expose an API secret in frontend code. Free-plan limits and terms may change. The shareable page uses query parameters; the direct image URL includes your custom public ID.
