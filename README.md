# Niyuktam Landing Page v2

A modern, professional landing page for Niyuktam - Digital Marketing Training & Mentorship Program.

## 🚀 Features

- Clean, minimalist design
- Modern responsive layout
- Student case studies with real results
- Pricing section
- FAQ accordion
- Form integration ready for Google Sheets
- Mobile-friendly
- Fast loading

## 📁 Files Included

```
niyuktam-landing/
├── index.html          (Main landing page)
├── README.md          (This file)
├── .gitignore         (Git ignore file)
└── vercel.json        (Vercel configuration)
```

## 🛠️ Setup & Deployment

### **Step 1: Create GitHub Repository**

1. Go to [GitHub.com](https://github.com)
2. Click **"New"** → Create new repository
3. **Repository name:** `niyuktam-landing`
4. **Description:** "Niyuktam Landing Page - Digital Marketing Training"
5. **Public:** Yes (so Vercel can access it)
6. Click **"Create repository"**

### **Step 2: Upload Files to GitHub**

**Option A: Using GitHub Web Interface (Easiest)**
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop or select:
   - `index.html`
   - `README.md`
   - `vercel.json`
   - `.gitignore`
3. Click **"Commit changes"**

**Option B: Using Git Command Line**
```bash
git clone https://github.com/YOUR_USERNAME/niyuktam-landing.git
cd niyuktam-landing
# Copy index.html, README.md, vercel.json, .gitignore here
git add .
git commit -m "Initial commit: Niyuktam landing page v2"
git push origin main
```

### **Step 3: Deploy to Vercel**

1. Go to [Vercel.com](https://vercel.com)
2. Click **"Sign Up"** or **"Sign In"** (use GitHub account for easiest setup)
3. Click **"Add New"** → **"Project"**
4. **Import Git Repository**
   - Paste your GitHub repo URL: `https://github.com/YOUR_USERNAME/niyuktam-landing`
   - Click **"Import"**
5. **Configure Project:**
   - **Project Name:** `niyuktam-landing`
   - **Framework:** Select **"Other"** (it's just HTML)
   - **Build Command:** Leave empty
   - **Output Directory:** Leave empty
6. Click **"Deploy"**

**That's it!** 🎉 Your site is live!

You'll get a FREE URL like: `https://niyuktam-landing.vercel.app`

### **Step 4: Connect Custom Domain (Optional)**

1. In Vercel → Your project → **Settings** → **Domains**
2. Add your custom domain: `niyuktam.com`
3. Copy the nameservers from Vercel
4. Go to your domain registrar (Namecheap, GoDaddy, etc.)
5. Update DNS nameservers
6. Wait 24-48 hours for propagation

---

## 📝 Important Notes

### **Form Integration**

The form currently alerts users on submission. To integrate with Google Sheets:

**Option 1: Use Formspree (Free)**
1. Go to [Formspree.io](https://formspree.io)
2. Create new form with your email
3. Get the form endpoint
4. Update form action in `index.html`

**Option 2: Use Google Apps Script (Free)**
1. Create Google Sheet
2. Create Apps Script to receive form data
3. Deploy as web app
4. Update form endpoint

**Option 3: Use Zapier (Paid)**
1. Connect Vercel form to Google Sheets
2. Auto-save submissions

---

## 🔧 Making Changes

### **To Update Landing Page:**

1. **Download** `index.html` from your GitHub repo
2. **Edit** it locally (in Notepad, VS Code, etc.)
3. **Save** changes
4. **Upload** updated file to GitHub
5. Vercel **automatically redeploys** (within 1-2 minutes)

### **Sections to Customize:**

- **Hero Section:** Update headline, subheadline, student results
- **Student Stories:** Update names, details, salaries
- **Pricing:** Update course pricing and details
- **Founder Section:** Add your real story and credentials
- **Contact Email:** Update in form for notifications

---

## 📊 Analytics (Optional)

Add Google Analytics to track visitors:

1. Get Google Analytics ID from [google.com/analytics](https://analytics.google.com)
2. Add this to the `<head>` section of `index.html`:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_GA_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_GA_ID');
</script>
```

---

## 🚀 Next Steps

1. **Deploy on Vercel** (5 minutes)
2. **Buy domain** from Namecheap/GoDaddy (₹300-1200/year)
3. **Connect domain** to Vercel
4. **Integrate form** with Google Sheets/Zapier
5. **Share URL** with prospects
6. **Track conversions** with Google Analytics

---

## 📞 Support

For issues:
- **Vercel Docs:** [vercel.com/docs](https://vercel.com/docs)
- **GitHub Help:** [docs.github.com](https://docs.github.com)
- **Form Integration:** Search "Formspree HTML form" or "Google Apps Script form"

---

## 📄 License

Free to use for Niyuktam business.

---

**Built with ❤️ for Niyuktam | Digital Marketing Training & Mentorship**
