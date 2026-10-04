# ImgVerifn

A lightweight product image verification demo that compares a seller-uploaded real photo with the display image and shows verdicts for sharpness, screen artifact detection, and product match.

## Included assets

The app keeps all product images in the public assets folder so they remain visible in the deployed website:

- public/images/display_photos
- public/images/real_photos

## Local development

```bash
npm install
npm run dev
```

## Production deployment

```bash
npm run deploy
```

This builds the app and publishes the generated static site to the GitHub Pages branch for the repository.
