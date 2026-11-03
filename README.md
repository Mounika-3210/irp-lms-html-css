# IRP LMS - HTML & CSS Assignment

This project recreates the three IRP LMS pages required by the assignment:

- `index.html` - Home page
- `courses.html` - Courses page with 9 YouTube videos
- `contact.html` - Contact Us page with a front-end-only form
- `style.css` - All website styling

## How to run locally

1. Open the project folder in VS Code.
2. Open `index.html` in a browser.
3. Click Home, Courses, and Contact Us to test the navigation.
4. On the Courses page, make sure the YouTube videos load.
5. Resize the browser to check mobile/tablet responsiveness.

## How to push to GitHub

### 1. Create a GitHub repository

Go to GitHub and create a **new Public repository**.

Suggested repository name:

`irp-lms-html-css`

Do not add another README if you are going to use the commands below.

### 2. Open the project in VS Code

Open the `irp-lms-website` folder.

Open the VS Code terminal:

`Terminal` -> `New Terminal`

### 3. Run these commands

```bash
git init
git add .
git commit -m "Create IRP LMS website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of the repository you created.

Example format:

```bash
git remote add origin https://github.com/YOUR_USERNAME/irp-lms-html-css.git
```

### 4. Check GitHub

Refresh your repository page. You should see:

- `index.html`
- `courses.html`
- `contact.html`
- `style.css`
- `README.md`

Make sure the repository is **Public**.

## How to publish with GitHub Pages

1. Open your GitHub repository.
2. Click **Settings**.
3. Click **Pages** in the left menu.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch: `main`.
6. Select folder: `/ (root)`.
7. Click **Save**.
8. Wait a little while for GitHub to build the site.
9. Return to **Settings -> Pages** to see your live website URL.

Your live URL will normally look like:

`https://YOUR_USERNAME.github.io/irp-lms-html-css/`

## Updating the website after changes

After editing your files, run:

```bash
git add .
git commit -m "Update website"
git push
```

GitHub Pages will automatically update the published site.

## Important assignment points covered

- HTML5 structure
- CSS3 styling
- Three required pages
- Consistent navigation
- Required color palette using CSS variables
- Required Cloudinary image assets
- Nine required YouTube iframe videos
- Responsive desktop/tablet/mobile layout
- Contact form without backend processing
- No JavaScript required
