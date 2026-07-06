# Yasmeena Akhter - GitHub Pages website

This is a clean static replacement for the Google Sites academic profile. It is designed for GitHub Pages and can be edited with any text editor.

## Files

- `index.html` - homepage
- `education/index.html` - education page
- `projects/index.html` - projects page
- `publications/index.html` - publications page
- `academic-experience/index.html` - academic experience page
- `activities-and-updates/index.html` - activities and updates page
- `contact/index.html` - contact page
- `assets/css/styles.css` - all styling
- `assets/img/profile.jpg` - profile image
- `.nojekyll` - tells GitHub Pages not to process this as a Jekyll site

## Launch as a personal GitHub Pages site

1. Create or sign in to a GitHub account.
2. Create a new public repository named exactly `YOUR_GITHUB_USERNAME.github.io`.
3. Copy all files from this folder into that repository.
4. Push the files:

```bash
git init
git branch -M main
git add .
git commit -m "Initial GitHub Pages website"
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io.git
git push -u origin main
```

5. On GitHub, open the repository and go to **Settings > Pages**.
6. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
7. Select **main** and **/(root)**, then click **Save**.
8. Open `https://YOUR_GITHUB_USERNAME.github.io/` after GitHub finishes deployment.

## Launch as a project GitHub Pages site

You can also use any repository name, such as `academic-website`. The URL will be `https://YOUR_GITHUB_USERNAME.github.io/academic-website/`. The relative links in this template should work in both personal-site and project-site deployments.

## Optional custom domain

1. In the repository, go to **Settings > Pages**.
2. Enter your custom domain, such as `yourdomain.com` or `www.yourdomain.com`.
3. Configure DNS at your domain provider.
4. After GitHub verifies the domain, enable **Enforce HTTPS**.

## Editing notes

- Replace the CV link if the current SharePoint CV link requires login.
- Update publications and accepted-paper status as soon as final metadata or DOI links are available.
- Edit colors in `assets/css/styles.css` under the `:root` section.
- Use compressed images for faster page loading.
