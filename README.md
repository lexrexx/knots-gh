![Bitcoin Knots v30](/social/knots-gh-cover.png)

# knots-gh - GitHub Pages Test Deployment

This repository hosts a **test deployment** of the Bitcoin Knots website on GitHub Pages, demonstrating how to serve a generated static site from a subdirectory path.

## 🧪 Purpose

This is a **testing and demonstration repository** showing how to:
- Deploy a Nuxt-generated static site to GitHub Pages
- Use a subdirectory structure (`/knots-gh/`) for the site
- Configure asset paths for GitHub Pages deployment

## 🌐 Live Test Site

**Access the test deployment here:**  
[https://lexrexx.github.io/knots-gh/](https://lexrexx.github.io/knots-gh/)

## 📁 Deployment Structure

- **Repository**: `lexrexx/knots-gh`
- **GitHub Pages URL**: `https://lexrexx.github.io/knots-gh/`
- **Base URL**: `/knots-gh/` (subdirectory structure)
- **For top-level domain**: Use the `knots-www` repository instead

## 🔧 How It Works

1. The site is generated from the **source repository** using Nuxt 4
2. Built with `baseURL="/knots-gh/"` for subdirectory deployment
3. Generated files are copied to this repository
4. GitHub Pages serves the site from the `/knots-gh/` path

## 🛠️ Making Updates

**All updates must be made in the source repository:**  
[https://github.com/lexrexx/bitcoinknots.org](https://github.com/lexrexx/bitcoinknots.org)

To regenerate this test site:
```bash
# In the source repository
npm run generate -- --baseURL="/knots-gh/"
# Files are output to: .output/public/
```

## 📝 Important Notes

- This is a **test deployment only**
- For production use with a top-level domain, see the `knots-www` repository
- All issues and development occur in the source repository
- This repository contains only generated static files

## 🔗 Related Repositories

- **Source Code**: [bitcoinknots.org](https://github.com/lexrexx/bitcoinknots.org) (where all development happens)
- **Top-Level Domain**: [knots-www](https://github.com/lexrexx/knots-www) (for `bitcoinknots.org`)
- **Test Deployment**: This repository (`knots-gh`)

## 🚀 Quick Deployment Example

This demonstrates the GitHub Pages subdirectory pattern:
```
Generated Site → Repository → GitHub Pages
   (Nuxt 4)    →  knots-gh  →  /knots-gh/
```

---

**This repository is automatically generated for testing purposes.**  
For production deployments or issue reporting, use the source repository.