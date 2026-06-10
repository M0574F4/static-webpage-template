# Setup After Using This Template

Follow these steps once you create a new repository from this template.

## 1. Create The Repository

On GitHub, create a new repository from this template.

Recommended options:

- Repository name: your project name
- Visibility: public, unless you know you need private
- Include all branches: off

## 2. Clone Or Push Your Project

If you start from GitHub:

```sh
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

If you start locally:

```sh
git init -b main
git add .
git commit -m "Initial static webpage"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

## 3. Enable GitHub Pages

Open your repository on GitHub.

Go to:

```text
Settings -> Pages
```

Under **Build and deployment**, set **Source** to:

```text
GitHub Actions
```

Do not choose the suggested Jekyll workflow.

Do not choose the suggested Static HTML workflow if this template already includes `.github/workflows/pages.yml`.

## 4. Run The First Deploy

After the first push to `main`, go to:

```text
Actions -> Deploy Static Site to GitHub Pages
```

If it did not run automatically, click:

```text
Run workflow
```

If it failed before Pages was enabled, click:

```text
Re-run jobs
```

## 5. Open The Website

After the workflow succeeds, your site will be available at:

```text
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/
```

## 6. Edit The Page

Change the blank starter message in:

```text
public/index.html
```

Then commit and push:

```sh
git add public/index.html public/styles.css
git commit -m "Update webpage"
git push
```

GitHub Pages will update automatically after the workflow finishes.
