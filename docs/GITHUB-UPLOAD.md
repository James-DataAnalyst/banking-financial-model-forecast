# GitHub Upload Guide

Use the repository name below so the URL in `portfolio/project-data.js` works without editing:

```text
banking-financial-model-forecast
```

## Option 1: Upload in the GitHub website

1. Sign in to GitHub and create a new public repository named `banking-financial-model-forecast`.
2. Do not add a README, `.gitignore`, or license during repository creation; they are already included here.
3. Open the new repository and choose **uploading an existing file**.
4. Upload the **contents inside this folder**, preserving the `assets`, `docs`, and `portfolio` folders.
5. Use a commit message such as `Add banking financial model portfolio case study`.
6. Confirm that the README images display correctly on the repository home page.

## Option 2: Upload with Git

From inside the extracted project folder, run:

```bash
git init
git add .
git commit -m "Add banking financial model portfolio case study"
git branch -M main
git remote add origin https://github.com/James-DataAnalyst/banking-financial-model-forecast.git
git push -u origin main
```

## Portfolio image setup

Copy the 17 files from `assets/screenshots` into:

```text
public/images/projects/banking-financial-model-forecast/
```

Then paste the object from `portfolio/project-data.js` into your website's projects data file.

## Final checks

- The repository is public.
- The README hero image loads.
- The disclaimer is visible near the top of the README.
- No Excel workbook, raw dataset, client file, or temporary file was uploaded.
- The website's **View case study** link opens the repository.
- The screenshot paths match the files copied into the website's `public` directory.
