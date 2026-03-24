# Calvin Pough - Professional Portfolio

A modern, responsive personal biography landing page showcasing 5+ years of procurement experience.

## 📋 What's Included

- **calvin-pough-bio.html** - Complete landing page (no external dependencies required)
- **IMG_0284.jpeg** - Professional headshot
- **README.md** - This file

## 🚀 Quick Start: Deploy to GitHub Pages (Free Hosting)

### Prerequisites
- A GitHub account (free at github.com)
- Git installed on your computer (or use GitHub Desktop)

### Step 1: Create a GitHub Repository

1. Go to **github.com** and log in
2. Click the **+** icon (top right) → **New repository**
3. Name your repository: `calvinpough` or `portfolio` (this becomes part of your URL)
4. Choose **Public** (required for free GitHub Pages hosting)
5. Do NOT initialize with README (we'll add one)
6. Click **Create repository**

### Step 2: Clone the Repository Locally

After creating the repository, GitHub will show you clone instructions. Choose one:

**Option A: Using Git Command Line**
```bash
git clone https://github.com/YOUR-USERNAME/calvinpough.git
cd calvinpough
```

**Option B: Using GitHub Desktop**
- Click **Code** → **Open with GitHub Desktop**
- Choose where to save the folder

### Step 3: Add Your Portfolio Files

1. Open your new local repository folder
2. Copy these files into it:
   - `calvin-pough-bio.html`
   - `IMG_0284.jpeg`
3. Rename `calvin-pough-bio.html` to `index.html` (GitHub Pages looks for this filename)

Your folder should now look like:
```
calvinpough/
├── index.html
├── IMG_0284.jpeg
└── README.md (this file)
```

### Step 4: Commit & Push to GitHub

**Using Git Command Line:**
```bash
git add .
git commit -m "Initial portfolio upload"
git push origin main
```

**Using GitHub Desktop:**
1. You'll see your files listed as changes
2. Enter commit message: "Initial portfolio upload"
3. Click **Commit to main**
4. Click **Push origin** (top right)

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar)
4. Under "Build and deployment" → "Source", select **Deploy from a branch**
5. Under "Branch", select **main** and **/root** folder
6. Click **Save**

GitHub will build your site. After ~1-2 minutes, you'll see:
> "Your site is live at https://YOUR-USERNAME.github.io/calvinpough/"

**That's it!** Your portfolio is now live on the internet. 🎉

---

## ✏️ Making Edits After Deployment

### Edit the HTML Content

1. Open `index.html` in a text editor (VS Code, Sublime, Notepad, etc.)
2. Make your changes (update text, change dates, modify sections)
3. Save the file
4. Commit and push:
   ```bash
   git add index.html
   git commit -m "Updated [section name]"
   git push origin main
   ```
5. Your live site updates automatically (usually within 1-2 minutes)

### Update Your Headshot

1. Replace `IMG_0284.jpeg` with a new image
2. Keep the same filename, or update the filename in `index.html` (search for `IMG_0284`)
3. Commit and push:
   ```bash
   git add IMG_0284.jpeg
   git commit -m "Updated headshot"
   git push origin main
   ```

### Common Edits in the HTML File

- **Navigation menu**: Search for `<nav>` section
- **Hero section text**: Search for `<h1>` (main heading)
- **About section**: Search for `<section id="about">`
- **Experience section**: Search for `<section id="experience">`
- **Contact email**: Search for `calvinpough@gmail.com` and replace with your email
- **Social links**: Search for LinkedIn, email, or phone number sections

---

## 🔒 Security & HTTPS

GitHub Pages provides **free HTTPS encryption** automatically. Your site URL will be:
- `https://YOUR-USERNAME.github.io/calvinpough/` (secure ✓)

No additional setup needed.

---

## 🌐 Optional: Use a Custom Domain

If you own a domain (e.g., calvinpough.com), you can point it to your GitHub Pages site:

1. Go to your domain registrar (GoDaddy, Namecheap, etc.)
2. Update DNS settings to point to GitHub Pages (registrar provides exact steps)
3. In your repository **Settings** → **Pages**, enter your custom domain
4. GitHub automatically enables HTTPS for your custom domain

[Detailed instructions here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## 📋 What Happens When Someone Visits Your Site?

1. Visitor goes to `https://your-username.github.io/calvinpough/`
2. GitHub serves `index.html` (your portfolio)
3. The page loads with your headshot, company logos, experience, and contact form
4. Contact form uses `mailto:` (opens their email client) or can be upgraded to form services like Formspree

---

## 🆘 Troubleshooting

**"I don't see my site live yet"**
- Wait 2-3 minutes after enabling GitHub Pages
- Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)
- Check that your filename is exactly `index.html` (case-sensitive)

**"Images aren't showing"**
- Ensure `IMG_0284.jpeg` is in the same folder as `index.html`
- Check that the filename in `index.html` matches exactly (including capitalization)

**"Changes aren't showing after I pushed"**
- Wait 1-2 minutes for GitHub to rebuild
- Hard refresh your browser cache

**"I accidentally deleted something"**
- GitHub keeps full version history
- Go to your repository's commits and revert to a previous version

---

## 📞 Next Steps

1. **Customize your content**: Edit `index.html` to add your LinkedIn recommendations, update company logos, or adjust colors
2. **Add a custom domain**: Point your personal domain to your GitHub Pages site
3. **Update form submissions**: Consider upgrading to Formspree.io for email notifications when someone submits the contact form
4. **Track visitors**: Add Google Analytics to see who's visiting your portfolio

---

## 📄 License & Support

This portfolio is your personal property. GitHub Pages is free and reliable for hosting static sites like this.

Need help? Check the [GitHub Pages documentation](https://docs.github.com/en/pages) or refer to the inline comments in `index.html`.

---

**Your portfolio is ready to go live. Push it to GitHub and share your link!** 🚀
