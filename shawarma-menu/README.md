# Roll Haven — Shawarma Menu
Responsive cream-and-purple menu inspired by the supplied reference. No installation or build required.

## Preview
Open index.html in a browser. Includes Arabic/English switching and working category filters.

## Edit
- menu.js: four sample items, prices and descriptions. Currency is Rs. as in the reference, not confirmed restaurant prices.
- index.html: restaurant name and general text.
- style.css: palette, layout and typography.
- assets/reference.jpg: supplied reference, displayed through SVG crop windows. Replace this sample imagery with restaurant-owned food photos before launch; for individual images replace each SVG in app.js with an img element and local image path.
No order/payment system, restaurant location or contact details are invented.

## GitHub to Vercel
1. Extract this ZIP.
2. Create a GitHub repository and upload all files INSIDE shawarma-menu, including assets. index.html should be at repository root.
3. Vercel → Add New → Project → import the repository.
4. Framework Preset: Other. Root Directory: repository root. No build command is required; serve the root directory (Output Directory: . if an override is needed).
5. Deploy. Test the production URL on mobile before printing a QR code.
6. Later commits to the configured production branch update the live website.

This deliverable is prepared source; it has not been pushed to GitHub or deployed to Vercel.
