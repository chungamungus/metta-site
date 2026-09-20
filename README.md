# mettapersonalchef.com

Source files for the Metta Personal Chef website. Pushing to the `main` branch deploys the site to AWS automatically (see `.github/workflows/deploy.yml`).

- Pages are plain HTML in the root folder; styles in `assets/css/main.css`; images in `images/`.
- `recipes/` is an unlinked section (noindex) that can be shared by URL.
- Deployment needs five GitHub secrets: `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`, `AWS_REGION`, `S3_BUCKET`, and (optional) `CLOUDFRONT_DISTRIBUTION_ID`.
