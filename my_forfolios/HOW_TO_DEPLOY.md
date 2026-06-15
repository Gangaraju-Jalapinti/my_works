# How to Deploy Your Portfolio on GitHub Pages (Free!)

## What you need
- A GitHub account (you already have one: github.com/Gangaraju-Jalapinti)
- The `index.html` file (downloaded from this chat)

---

## Step 1 — Create a special GitHub repository

1. Go to **github.com** and log in
2. Click the **+** button (top right) → **New repository**
3. Name it exactly: `Gangaraju-Jalapinti.github.io`
   *(must match your username exactly — capital G and J)*
4. Set it to **Public**
5. Check ✅ **Add a README file**
6. Click **Create repository**

---

## Step 2 — Upload your portfolio file

1. Open the repo you just created
2. Click **Add file** → **Upload files**
3. Drag and drop the `index.html` file you downloaded
4. In the commit message box, type: `Add portfolio website`
5. Click **Commit changes**

---

## Step 3 — Enable GitHub Pages

1. In your repo, click **Settings** (top tabs)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**

---

## Step 4 — Wait 2 minutes, then visit your site!

Your site will be live at:
**https://Gangaraju-Jalapinti.github.io**

GitHub takes 1–3 minutes to deploy. Refresh after 2 minutes.

---

## Step 5 — Personalize before uploading

Open `index.html` in Notepad (Windows) or TextEdit (Mac) and change:

| Find this | Replace with |
|-----------|-------------|
| `gangaraju.jalapinti@gmail.com` | Your actual email |
| `+91 XXXXXXXXXX — add your number` | Your phone number |

---

## Optional: Connect a contact form (free)

The contact form needs a free service called Formspree:

1. Go to **formspree.io** → Sign up free
2. Create a new form — copy the form endpoint (looks like `https://formspree.io/f/xyzabc`)
3. Open `index.html`, find this line:
   ```
   onclick="alert('To enable this form..."
   ```
4. Replace that whole button with:
   ```html
   <form action="https://formspree.io/f/YOUR_CODE" method="POST">
   ```
   And change the button to `type="submit"`

---

## Your live URL to add everywhere
```
https://Gangaraju-Jalapinti.github.io
```
Add this to:
- LinkedIn profile (website field)
- GitHub bio
- Your resume
- Email signature

