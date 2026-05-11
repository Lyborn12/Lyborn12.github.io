# VioletTech Solutions — Website

Microsoft Power Platform consultancy website for VioletTech Solutions.

## Tech Stack
- Pure HTML, CSS, JavaScript — no frameworks, no build tools
- Google Fonts: DM Serif Display, DM Sans, DM Mono
- Hosted free on GitHub Pages

## Folder Structure
```
violettech/
├── index.html          ← Main website file
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Nav, animations, form handling
└── README.md
```

## How to Deploy on GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up if you haven't already.

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it exactly: `violettechsolutions.github.io`  
   (Replace "violettechsolutions" with your GitHub username if different)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. In the new repo, click **Add file** → **Upload files**
2. Upload all files keeping the folder structure:
   - `index.html` (root)
   - `css/style.css`
   - `js/main.js`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. Click **Save**

### Step 5 — Your site is live!
After 1–2 minutes, your site will be live at:
`https://violettechsolutions.github.io`

## Custom Domain (Optional — Free)
If you buy a domain (e.g. violettechsolutions.co.za from ~R150/year):
1. Go to Settings → Pages → Custom domain
2. Enter your domain name and save
3. At your domain registrar, add a CNAME record pointing to `violettechsolutions.github.io`

## Updating the Site
To update any content, simply edit the files and re-upload them to GitHub,
or use the GitHub web editor (click any file → pencil icon to edit).

## Contact Form
The current contact form shows a success message on submit but does NOT
actually send emails (no backend). To make it send real emails for free:

1. Go to https://formspree.io and sign up (free plan: 50 submissions/month)
2. Create a new form — you'll get a form endpoint URL
3. In index.html, change the `<form>` tag to:
   `<form action="https://formspree.io/f/YOUR_ID" method="POST">`
4. Remove the `onsubmit="handleSubmit(event)"` attribute
5. Formspree will email you every submission to nemolyborn@gmail.com

## Colour Palette
- Navy:   #0F172A
- Violet: #7C3AED
- Teal:   #2DD4BF
- Slate:  #64748B

## Contact
Lyborn Nemo · nemolyborn@gmail.com · linkedin.com/in/lyborn-nemo
