# CrossFit Blaze Seniors Landing Page

A dedicated landing page for adults 50+ interested in CrossFit at CrossFit Blaze in Naples, FL.

## 🌐 Live Site

Once deployed to GitHub Pages:
**URL:** https://blazedbarbell.github.io/seniors-crossfit-blaze/

Or with custom domain:
**URL:** https://seniors.crossfitblaze.com

## 📝 About This Page

This landing page addresses the common concern: *"Am I too old for CrossFit?"*

### Features:
- ✅ Hero section with direct value proposition
- ✅ Answers to "Am I too old?" 
- ✅ 6 benefit cards (independence, bone health, mental sharpness, community, energy, personalization)
- ✅ Step-by-step walkthrough of first 3 free classes
- ✅ FAQ accordion (10 common questions)
- ✅ Testimonials section (ready for real stories)
- ✅ Clear CTA for 3 free classes
- ✅ Contact information

## 🚀 Deployment

This site is automatically deployed using **GitHub Actions** + **GitHub Pages**.

### How it works (Auto-Deployment):
1. Push changes to the `main` branch
2. GitHub Actions workflow triggers automatically
3. Site deploys to GitHub Pages within 1-2 minutes
4. No manual steps needed!

### GitHub Actions Workflow

The workflow (`.github/workflows/deploy-static.yml`) handles:
- ✅ Checkout code on every push to `main`
- ✅ Configure GitHub Pages
- ✅ Upload site files as artifact
- ✅ Deploy to GitHub Pages

**View workflow runs:** https://github.com/blazedbarbell/seniors-crossfit-blaze/actions

### To make changes:

**Option 1: Edit directly on GitHub**
1. Go to https://github.com/blazedbarbell/seniors-crossfit-blaze
2. Click on `index.html`
3. Click the pencil icon to edit
4. Make changes and commit

**Option 2: Local editing**
```bash
git clone https://github.com/blazedbarbell/seniors-crossfit-blaze.git
cd seniors-crossfit-blaze
# Edit index.html
git add .
git commit -m "Update landing page"
git push origin main
```

## 📊 Analytics (Optional)

To track page views and conversions, add Google Analytics:

1. Create a Google Analytics account
2. Get your tracking ID (G-XXXXXXXXXX)
3. Add this code before the closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## 🎯 Custom Domain (Optional)

To use a custom domain like `seniors.crossfitblaze.com`:

1. Create a file named `CNAME` in this repo with your domain:
   ```
   seniors.crossfitblaze.com
   ```

2. Add a DNS record with your domain provider:
   - Type: CNAME
   - Name: seniors
   - Value: blazedbarbell.github.io

3. Wait 5-10 minutes for DNS to propagate

4. Enable HTTPS in GitHub repo settings

## 📧 Email Templates

See `/templates/senior-crossfit-email-templates.md` for ready-to-use email responses.

## 🎨 Brand Colors

- Primary Red: `#e94560`
- Dark Navy: `#1a1a2e`
- Light Background: `#f8f9fa`
- White: `#ffffff`
- Success Green: `#4caf50`

## 📞 Contact

CrossFit Blaze  
3355 Mercantile Ave, Naples, FL 34104  
📞 (239) 289-9275  
✉️ jason@crossfitblaze.com

---

*Built with 💪 by Daneel for CrossFit Blaze*
