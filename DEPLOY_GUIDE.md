# 📋 Step-by-Step GitHub Pages Deployment Guide

## 🎯 Goal
Deploy Traeceet's privacy policy to GitHub Pages for App Store submission.

## ⏱ Estimated Time
**Total**: 10-15 minutes (including GitHub account setup if needed)

---

## 🔧 Prerequisites

- [ ] GitHub account (free) - [Sign up here](https://github.com/join)
- [ ] Support email address ready
- [ ] Files from `github-pages-privacy` folder

---

## 📋 Step-by-Step Instructions

### Step 1: Prepare Your Email (2 minutes)

1. **Decide on support email**:
   - Personal: `your.name@gmail.com`
   - Professional: `support@yourdomain.com`
   - Temporary: Create new Gmail if needed

2. **Open `index.html`** in text editor
3. **Find line ~160**: `[SUPPORT_EMAIL_PLACEHOLDER]`
4. **Replace with your email**: `support@yourdomain.com`
5. **Save file**

### Step 2: Create GitHub Repository (3 minutes)

1. **Go to GitHub.com** → Sign in
2. **Click green "New" button** (top left)
3. **Repository settings**:
   - **Name**: `traeceet-privacy-policy`
   - **Visibility**: ✅ **Public** (required for free Pages)
   - ✅ **Check "Add a README file"**
4. **Click "Create repository"**

### Step 3: Upload Privacy Policy (2 minutes)

1. **In your new repository**, click "uploading an existing file"
2. **Drag `index.html`** into the upload area
3. **Scroll down** to "Commit new file"
4. **Commit message**: `Add Traeceet privacy policy`
5. **Click "Commit changes"**

### Step 4: Enable GitHub Pages (3 minutes)

1. **Click "Settings" tab** (top of repository)
2. **Scroll down** to "Pages" in left sidebar
3. **Source settings**:
   - **Source**: "Deploy from a branch"
   - **Branch**: `main` (should be selected automatically)
   - **Folder**: `/ (root)`
4. **Click "Save"**
5. **Wait for confirmation** (green checkmark appears)

### Step 5: Get Your URL (1 minute)

1. **Your URL format**:
   ```
   https://[your-github-username].github.io/traeceet-privacy-policy/
   ```
   
2. **Example**:
   - Username: `filipdroszcz`
   - URL: `https://filipdroszcz.github.io/traeceet-privacy-policy/`

3. **Wait 5-10 minutes** for deployment
4. **Test the URL** in your browser

### Step 6: Verify Deployment (2 minutes)

✅ **Checklist**:
- [ ] Privacy policy page loads
- [ ] All sections visible and formatted correctly
- [ ] Your support email shows (not placeholder)
- [ ] Table of contents links work
- [ ] Mobile responsive (test on phone)

---

## 🎯 Final URL for App Store Connect

Once verified, use this URL in App Store Connect:

**Privacy Policy URL**:
```
https://[your-username].github.io/traeceet-privacy-policy/
```

---

## 🚨 Troubleshooting

**Page not loading after 10 minutes?**
- Check repository is **Public**
- Verify GitHub Pages is enabled
- Try incognito/private browser window

**404 Error?**
- Ensure file is named exactly `index.html`
- Check it's in root directory (not in a folder)

**Support email still showing placeholder?**
- Edit `index.html` directly on GitHub
- Search for `[SUPPORT_EMAIL_PLACEHOLDER]`
- Replace and commit changes

---

## ✅ Success Criteria

🎉 **You're done when**:
- Privacy policy loads at your GitHub Pages URL
- Your support email is visible
- Page is mobile-friendly
- All links work correctly

**Next**: Use the URL in App Store Connect privacy policy field.

---

**Need Help?** 
- GitHub Pages Docs: https://docs.github.com/en/pages
- GitHub Support: https://support.github.com/