# Website Deployment Guide

This guide will help you make your personal website publicly accessible on the internet.

## Option 1: GitHub Pages (Recommended - Free)

### Method A: Using Repository Settings (Easiest)

1. **Go to your GitHub repository**: https://github.com/besthvr12/Personal-Website

2. **Enable GitHub Pages**:
   - Click on **Settings** tab
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select the branch: `claude/create-personal-website-011CUxGHZkr4TVe8e7557JUW`
   - Select folder: `/ (root)`
   - Click **Save**

3. **Wait for deployment** (1-2 minutes)

4. **Your website will be live at**:
   ```
   https://besthvr12.github.io/Personal-Website/
   ```

### Method B: Using GitHub Actions (Automated)

The GitHub Actions workflow has already been set up. To use it:

1. **Go to Repository Settings** → **Pages**
2. Under **Source**, select: **GitHub Actions**
3. The workflow will automatically deploy on every push
4. Your site will be live at: `https://besthvr12.github.io/Personal-Website/`

---

## Option 2: Netlify (Very Easy - Free)

### Method A: Drag and Drop (No Git Required)

1. **Go to**: https://app.netlify.com/drop
2. **Drag and drop** your entire `Personal-Website` folder
3. **Done!** You'll get a URL like: `https://random-name-123456.netlify.app`
4. You can customize the domain in Site Settings

### Method B: Connect to GitHub (Recommended)

1. **Sign up/Login** at: https://app.netlify.com
2. Click **Add new site** → **Import an existing project**
3. Choose **GitHub** and authorize Netlify
4. Select repository: `besthvr12/Personal-Website`
5. Branch: `claude/create-personal-website-011CUxGHZkr4TVe8e7557JUW`
6. Build settings: (leave empty - it's a static site)
7. Click **Deploy site**
8. Your site will be live at: `https://yoursite.netlify.app`

**Custom Domain**: You can add a custom domain in Site Settings → Domain Management

---

## Option 3: Vercel (Free)

1. **Go to**: https://vercel.com
2. **Sign up** with GitHub
3. Click **Add New** → **Project**
4. **Import** your `Personal-Website` repository
5. Branch: `claude/create-personal-website-011CUxGHZkr4TVe8e7557JUW`
6. Framework Preset: **Other**
7. Click **Deploy**
8. Your site will be live at: `https://yoursite.vercel.app`

---

## Option 4: Render (Free)

1. **Go to**: https://render.com
2. **Sign up** with GitHub
3. Click **New** → **Static Site**
4. Connect repository: `besthvr12/Personal-Website`
5. Branch: `claude/create-personal-website-011CUxGHZkr4TVe8e7557JUW`
6. Build command: (leave empty)
7. Publish directory: `.` (current directory)
8. Click **Create Static Site**
9. Your site will be live at: `https://yoursite.onrender.com`

---

## Option 5: Cloudflare Pages (Free)

1. **Go to**: https://pages.cloudflare.com
2. **Sign up/Login**
3. Click **Create a project**
4. Connect to **GitHub**
5. Select repository: `besthvr12/Personal-Website`
6. Branch: `claude/create-personal-website-011CUxGHZkr4TVe8e7557JUW`
7. Build settings: (leave empty)
8. Click **Save and Deploy**
9. Your site will be live at: `https://yoursite.pages.dev`

---

## Quick Comparison

| Service | Speed | Custom Domain | SSL | Best For |
|---------|-------|---------------|-----|----------|
| **GitHub Pages** | Fast | Free (subdomain) | Yes | GitHub users |
| **Netlify** | Very Fast | Free | Yes | Easy deployment |
| **Vercel** | Very Fast | Free | Yes | Modern sites |
| **Render** | Fast | Free | Yes | Full-stack apps |
| **Cloudflare Pages** | Ultra Fast | Free | Yes | Performance |

---

## Recommended Steps

### For Quickest Deployment (5 minutes):

1. **Use Netlify Drag & Drop**:
   - Go to https://app.netlify.com/drop
   - Drag your website folder
   - Get instant URL

### For Best Long-term Solution:

1. **Use GitHub Pages** (it's already set up!):
   - Go to your GitHub repo settings
   - Enable GitHub Pages from your branch
   - Get `https://besthvr12.github.io/Personal-Website/`

---

## Custom Domain Setup (Optional)

If you want your own domain (e.g., `harshverma.com`):

1. **Buy a domain** from:
   - Namecheap (~$10/year)
   - Google Domains (~$12/year)
   - Cloudflare (~$9/year)

2. **Configure DNS** in your hosting service:
   - GitHub Pages: Add CNAME record
   - Netlify: Automatic setup
   - Vercel: Automatic setup

---

## Troubleshooting

### GitHub Pages not working?
- Make sure the repository is **public**
- Check that Pages is enabled in Settings
- Wait 2-3 minutes for deployment

### CSS/JS not loading?
- Check browser console for errors
- Ensure all file paths are relative (they are in our setup)
- Clear browser cache

### Site not updating?
- Wait a few minutes for deployment
- Clear browser cache (Ctrl+F5)
- Check deployment status in your hosting service

---

## Monitoring Your Website

After deployment, you can add:

- **Google Analytics** - Track visitors
- **Google Search Console** - SEO monitoring
- **Cloudflare** - CDN and security

---

## Need Help?

If you encounter any issues:

1. Check the hosting service's documentation
2. Look at deployment logs
3. Verify all files are committed and pushed
4. Contact support for the hosting service

---

**Congratulations!** 🎉 Your website will be live and accessible to anyone worldwide!
