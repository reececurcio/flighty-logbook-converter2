FLIGHTY CONVERTER APP ICON FILES

Use these files in your GitHub Pages repository:

- icon.png                 Main 1024x1024 icon
- apple-touch-icon.png     iPhone Home Screen icon
- icon-512.png             PWA 512x512 icon
- icon-192.png             PWA 192x192 icon
- favicon-32.png           Browser tab icon
- icon.svg                 Exact same image embedded in SVG format

Recommended replacement steps:
1. Delete the old icon.svg and any old icon PNG files from GitHub.
2. Upload all files from this folder.
3. In index.html, use:
   <link rel="apple-touch-icon" href="apple-touch-icon.png">
   <link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
4. In manifest.webmanifest, use icon-192.png and icon-512.png.
5. Commit the changes.
6. Delete the old Home Screen app icon from your iPhone.
7. Clear Safari website data for the GitHub Pages site.
8. Open the site again and choose Share > Add to Home Screen.
