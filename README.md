# Pameru — static site

Australian construction + field CRM marketing site. Plain HTML, CSS, and JavaScript (no build step).

Contact: **info@pameru.com**

## Host on GitHub Pages (simple path)

### 1. Create a new repository on GitHub

- Name it `pameru` (or anything you like).
- Leave it **empty** or add a README only — you will push this folder’s contents.

### 2. Put the site at the repository root

The repository root should contain:

- `index.html`, `about.html`, `contact.html`, `crm.html`, `services.html`
- `css/`, `js/`
- `.nojekyll` (stops Jekyll from touching the site)

From your machine (adjust the GitHub URL to your account):

```bash
cd "/Users/binayapuri/Desktop/deakin/T3/SIT744 - Deep Learning/pameru"
git init
git add .
git commit -m "Initial Pameru static site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pameru.git
git push -u origin main
```

### 3. Turn on GitHub Pages

1. On GitHub, open the repo → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**.
4. Save. After a minute or two, the site will be at:

   `https://YOUR_USERNAME.github.io/pameru/`

   (If the repository is named `YOUR_USERNAME.github.io`, the site root is `https://YOUR_USERNAME.github.io/` instead.)

### 4. Custom domain (optional)

If you later point **pameru.com** at GitHub Pages, add a `CNAME` file in the repo root whose only line is:

```text
pameru.com
```

Then configure DNS at your registrar per [GitHub’s custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

All asset links are **relative** (`css/styles.css`, `about.html`), so the site works both on GitHub Pages project URLs and at a custom apex domain.
# Pameru
# Pameru
