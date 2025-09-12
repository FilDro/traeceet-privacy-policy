# Traeceet Privacy Policy - GitHub Pages Setup

This repository contains the privacy policy for the Traeceet iOS app, configured for deployment via GitHub Pages.

## 🚀 Quick Deployment

### Option 1: New Repository (Recommended)

1. **Create new GitHub repository**:
   - Go to [GitHub.com](https://github.com) → New Repository
   - Name: `traeceet-privacy-policy`
   - Set to **Public** (required for free GitHub Pages)
   - ✅ Check "Add a README file"
   - Click "Create repository"

2. **Upload files**:
   - Click "uploading an existing file"
   - Drag and drop `index.html` from this folder
   - Commit with message: "Add Traeceet privacy policy"

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
   - Click "Save"

4. **Get your URL**:
   - Your privacy policy will be live at:
   - `https://[your-username].github.io/traeceet-privacy-policy/`

### Option 2: Add to Existing Repository

1. **Create docs folder** in your existing repo:
   ```
   your-repo/
   └── docs/
       └── index.html  (copy the index.html file here)
   ```

2. **Enable GitHub Pages**:
   - Repository Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main`
   - Folder: `/docs`
   - Click "Save"

3. **Your URL**:
   - `https://[your-username].github.io/[repo-name]/`

## 📧 Add Your Support Email

Before deploying, replace the placeholder in `index.html`:

**Find this line** (around line 160):
```html
<p><strong>Email:</strong> [SUPPORT_EMAIL_PLACEHOLDER]<br>
```

**Replace with**:
```html
<p><strong>Email:</strong> your-support@email.com<br>
```

## 📱 For App Store Connect

Once deployed, use this URL in App Store Connect:
- **Privacy Policy URL**: `https://[your-username].github.io/traeceet-privacy-policy/`

## 🔧 Troubleshooting

**GitHub Pages not working?**
- Ensure repository is **Public**
- Wait 5-10 minutes after enabling GitHub Pages
- Check repository Settings → Pages for status

**Custom Domain (Optional)**:
- Add `CNAME` file with your domain name
- Configure DNS with your domain provider
- Enable "Enforce HTTPS" in Pages settings

## 📝 File Structure

```
github-pages-privacy/
├── index.html          # Privacy policy (main page)
└── README.md          # This setup guide
```

## ✅ Verification

After deployment:
1. Visit your GitHub Pages URL
2. Verify privacy policy loads correctly
3. Test on mobile devices
4. Check all internal links work
5. Copy final URL for App Store Connect

## 🔄 Updates

To update the privacy policy:
1. Edit `index.html` on GitHub (or locally)
2. Update the "Last Updated" date
3. Commit changes
4. GitHub Pages automatically rebuilds (2-5 minutes)

## 📞 Support

If you encounter issues:
- Check [GitHub Pages documentation](https://docs.github.com/en/pages)
- Verify repository is public
- Contact GitHub Support for technical issues

---

**Total Setup Time**: 5-10 minutes  
**Cost**: Free (with public repository)  
**Maintenance**: Update HTML file as needed