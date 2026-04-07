# 🚀 QUICK DEPLOYMENT GUIDE - Niyuktam Landing Page v2

## ⏱️ Time Required: 10-15 minutes

---

## 📋 FILES YOU NEED

Download these 4 files from outputs:
1. ✅ `index.html` - Main landing page
2. ✅ `README.md` - Documentation
3. ✅ `vercel.json` - Vercel config
4. ✅ `.gitignore` - Git config

---

## 🎯 STEP 1: Create GitHub Repository (3 minutes)

### **Step 1.1: Go to GitHub**
- Open: https://github.com
- Sign in (or create account)
- Click **"+"** → **"New repository"**

### **Step 1.2: Create Repo**
- **Repository name:** `niyuktam-landing`
- **Description:** "Niyuktam Digital Marketing Training Landing Page"
- **Visibility:** PUBLIC
- **Don't initialize** anything
- Click **"Create repository"**

### **Step 1.3: Upload Files**
- Click **"Upload files"** button
- **Drag and drop** these 4 files:
  - `index.html`
  - `README.md`
  - `vercel.json`
  - `.gitignore`
- Click **"Commit changes"**

✅ **Your GitHub repo is now ready!**

Get your repo URL: `https://github.com/YOUR_USERNAME/niyuktam-landing`

---

## 🎯 STEP 2: Deploy to Vercel (5 minutes)

### **Step 2.1: Go to Vercel**
- Open: https://vercel.com
- Click **"Sign Up"** (use GitHub for easiest setup)
- Authorize with your GitHub account

### **Step 2.2: Import Project**
- After login, click **"Add New"** → **"Project"**
- Paste your GitHub repo URL:
  ```
  https://github.com/YOUR_USERNAME/niyuktam-landing
  ```
- Click **"Import"**

### **Step 2.3: Configure Project**
- **Project Name:** `niyuktam-landing` (or any name)
- **Framework:** Select **"Other"**
- **Build Command:** Leave empty
- **Output Directory:** Leave empty
- **Environment Variables:** None needed (for now)

### **Step 2.4: Deploy**
- Click **"Deploy"**
- Wait 1-2 minutes for deployment to complete
- You'll see: **"Congratulations! Your site is live"** ✅

### **Step 2.5: Get Your URL**
Vercel gives you a FREE URL like:
```
https://niyuktam-landing.vercel.app
```

✅ **Your site is now LIVE online!** 🎉

---

## 🌐 STEP 3: Connect Custom Domain (Optional - 5 minutes)

Only do this if you have a custom domain like `niyuktam.com`

### **Step 3.1: Add Domain in Vercel**
- In Vercel, go to your project
- Click **"Settings"** → **"Domains"**
- Click **"Add"**
- Enter your domain: `niyuktam.com`
- Click **"Add"**

### **Step 3.2: Update DNS (at Domain Registrar)**
- Login to your domain registrar (Namecheap, GoDaddy, etc.)
- Go to **"DNS Settings"** or **"Nameservers"**
- Replace nameservers with Vercel's nameservers (shown in Vercel)
- Save changes

### **Step 3.3: Wait for DNS Propagation**
- Takes 24-48 hours
- Your domain will work once propagated

✅ **Your custom domain will be live!**

---

## ✅ VERIFY YOUR DEPLOYMENT

### **Check Your Site**
1. Open: `https://niyuktam-landing.vercel.app` (or your custom domain)
2. Verify all sections load:
   - ✅ Hero section
   - ✅ Student stories
   - ✅ Pricing
   - ✅ FAQ
   - ✅ Form
3. Test mobile view (resize browser)

### **Test Form**
1. Fill the form
2. Click "Claim Free Trial"
3. Should show success message

---

## 🔄 HOW TO UPDATE YOUR SITE

### **Making Changes**
1. Download `index.html` from GitHub
2. Edit in Notepad or VS Code
3. Make your changes
4. Go to GitHub repo
5. Click **"Upload files"**
6. Select updated `index.html`
7. Click **"Commit"**
8. **Vercel automatically redeploys** (1-2 minutes)

### **Popular Changes to Make**
- Update student names/salaries
- Change pricing
- Add your founder story
- Update CTA text
- Change colors/fonts

---

## 📊 NEXT: Form Integration (Optional)

To save form submissions to Google Sheets:

**Option A: Formspree (Simplest)**
1. Go to https://formspree.io
2. Create new form
3. Get endpoint
4. Update form in `index.html`

**Option B: Google Apps Script (Free)**
1. Create Google Sheet
2. Create script to receive data
3. Deploy as web app
4. Update form endpoint

---

## 🎯 FINAL CHECKLIST

- [ ] Created GitHub repo
- [ ] Uploaded 4 files
- [ ] Deployed to Vercel
- [ ] Got free URL (niyuktam-landing.vercel.app)
- [ ] Site loads properly
- [ ] Form works
- [ ] (Optional) Connected custom domain
- [ ] (Optional) Set up form integration

---

## 🎉 YOU'RE DONE!

Your Niyuktam landing page is now:
✅ **Live online** (Vercel URL)
✅ **Mobile-friendly**
✅ **Fast loading**
✅ **Professional design**
✅ **Ready for students**

---

## 📞 NEED HELP?

- **Vercel won't deploy?** → Check your files are correct
- **Form not working?** → Use Formspree (see above)
- **Custom domain issues?** → Wait 48 hours for DNS propagation
- **Design changes?** → Edit `index.html` and re-upload

---

## 🚀 QUICK LINKS

- **GitHub:** https://github.com
- **Vercel:** https://vercel.com
- **Formspree:** https://formspree.io
- **Namecheap:** https://namecheap.com
- **GoDaddy:** https://godaddy.com

---

**Happy deploying! 🎊**
**Your Niyuktam landing page is now live and ready to convert students!**
