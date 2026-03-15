# कांताई Skin Care — Website Deployment Guide

## 🗂️ Project Structure
```
kantai-site/
├── index.html       ← Main website file
├── netlify.toml     ← Netlify configuration
├── .gitignore       ← Git ignore rules
└── README.md        ← This file
```

---

## 🚀 Step-by-Step Deployment

### STEP 1 — GitHub वर Repository तयार करा

1. **github.com** वर जा → Sign in / Sign up करा
2. Right top corner मध्ये **"+"** button दाबा → **"New repository"** select करा
3. खालील details भरा:
   - **Repository name:** `kantai-skin-care` (किंवा कोणतेही नाव)
   - **Description:** Kantai Skin Care Clinic Website
   - **Visibility:** ✅ **Public** select करा (Netlify free deploy साठी)
   - **Initialize:** ✅ "Add a README file" **uncheck** करा
4. **"Create repository"** button दाबा

---

### STEP 2 — Files GitHub वर Upload करा

Repository तयार झाल्यावर:

1. **"uploading an existing file"** link दाबा
2. या 3 files drag & drop करा:
   - `index.html`
   - `netlify.toml`
   - `.gitignore`
3. Commit message लिहा: `Initial deploy - Kantai Skin Care website`
4. **"Commit changes"** button दाबा ✅

---

### STEP 3 — Netlify वर Deploy करा

1. **app.netlify.com** वर जा → **"Sign up"** करा
2. **"Sign up with GitHub"** select करा → GitHub account connect करा
3. Dashboard वर **"Add new site"** → **"Import an existing project"** दाबा
4. **"Deploy with GitHub"** select करा
5. तुमची `kantai-skin-care` repository search करा → Select करा
6. Deploy settings:
   - **Branch:** `main`
   - **Build command:** *(रिकामे ठेवा)*
   - **Publish directory:** `.` (dot — current folder)
7. **"Deploy site"** button दाबा 🚀

---

### STEP 4 — Live Link मिळवा

Deploy झाल्यावर Netlify तुम्हाला एक free link देईल:
```
https://random-name-123456.netlify.app
```

हीच तुमची **Live Website** आहे! Share करा 🎉

---

## 🌐 Custom Domain Setup (Optional)

स्वतःचा domain जोडायचा असेल तर (उदा. `kantaiskinclinic.com`):

1. Netlify Dashboard → **"Domain settings"** → **"Add custom domain"**
2. Domain name type करा
3. Domain provider (GoDaddy/Hostinger) मध्ये जाऊन **DNS settings** update करा:
   - Netlify दाखवलेले **Nameservers** copy करा
   - Domain provider च्या DNS मध्ये paste करा
4. 24-48 तासांत live होईल ✅

---

## 🔄 Website Update कसे करायचे?

Website मध्ये बदल करायचे असतील तेव्हा:

1. GitHub वर जा → `index.html` file open करा
2. **Edit (pencil icon)** दाबा → Changes करा
3. **"Commit changes"** दाबा
4. Netlify **automatically** 1-2 minutes मध्ये **re-deploy** करेल ✅

---

## ✅ Checklist Before Going Live

- [ ] WhatsApp number verify केला का? (8788889366)
- [ ] Google Maps link update केला का?
- [ ] Website mobile वर test केली का?
- [ ] Doctor photo correctly दिसत आहे का?
- [ ] Appointment form WhatsApp वर redirect होत आहे का?

---

*Built with ❤️ for Kantai Skin Care | Parola, Jalgaon*
