# Tech-X Assets

## Images Folder
Place your Tech-X logo files in the `images/` folder.

### Recommended Logo Files:
- `logo.png` - PNG format logo (recommended size: 200x50px or similar ratio)
- `logo.svg` - SVG format logo (preferred for web - scalable)
- `favicon.ico` - Website favicon (16x16px, 32x32px)

### How to Add Your Logo:
1. Upload your logo file to `assets/images/`
2. In `index.html` and `updates.html`, uncomment the logo image line:
   ```html
   <!-- <img src="assets/images/logo.png" alt="Tech-X Logo" class="h-8 w-auto"> -->
   ```
   Remove the `<!--` and `-->` to make it active.

3. Update the `src` attribute to match your logo filename.

### Logo Guidelines:
- Keep file size under 100KB for fast loading
- Use transparent background for PNG files
- Ensure logo looks good at small sizes (navbar height is 32px)
- SVG format is preferred for crisp display on all screen sizes