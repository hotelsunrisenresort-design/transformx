# TransformX AI — GitHub Pages Deployment Guide

## 🚀 Quick Deploy to GitHub Pages (Free)

### Step 1: Create a GitHub account
1. Go to https://github.com and sign up for free.

### Step 2: Create a new repository
1. Click the **+** button → **New repository**
2. Name it: `transformx-ai`
3. Set to **Public**
4. **Do NOT** initialize with README (leave unchecked)
5. Click **Create repository**

### Step 3: Upload your files
1. On the empty repository page, click **uploading an existing file**
2. Upload ALL files from the `transformx-ai-html` folder:
   - `index.html`
   - `auth.html`
   - `onboarding.html`
   - `app.html`
   - `css/style.css`
   - `js/data.js`
   - `js/utils.js`
3. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to **Settings** tab in your repository
2. Scroll to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Select **main** branch, **/ (root)** folder
5. Click **Save**

### Step 5: Your site is live! 🎉
After 1-3 minutes, your site will be available at:
```
https://YOUR_USERNAME.github.io/transformx-ai/
```

---

## 📂 File Structure
```
transformx-ai-html/
├── index.html          # Landing page
├── auth.html           # Login / Signup / OTP
├── onboarding.html     # 10-step profile setup wizard
├── app.html            # Main application (all features)
├── css/
│   └── style.css       # Complete design system
└── js/
    ├── data.js         # All static data (500+ foods, 42 exercises, etc.)
    └── utils.js        # All utility functions
```

---

## ✅ What's Working (No API Key Needed)
- ✅ User registration & login (local storage)
- ✅ 10-step personalized onboarding wizard
- ✅ Dashboard with real-time stats
- ✅ Workout logger with sets/reps/weight tracking
- ✅ Rest timer with sound
- ✅ Personal record tracking
- ✅ 42 exercises with instructions
- ✅ 500+ foods nutrition database
- ✅ Meal logging with macro tracking
- ✅ Water intake tracking
- ✅ Progress measurements (14 body parts)
- ✅ Progress photos (stored locally)
- ✅ Calendar view
- ✅ AI chat with smart demo responses
- ✅ Daily habits & routines
- ✅ Journal with mood & tags
- ✅ Achievements & XP system
- ✅ Supplement guide
- ✅ Dark / Light mode
- ✅ CSV/PDF export
- ✅ Gamification (XP, levels, streaks)
- ✅ BMI/BMR/TDEE calculator

## 🤖 Add Real AI Chat (Optional)
1. Get an API key from https://platform.openai.com
2. In the app, go to AI Coach section
3. Click "Add API Key"
4. Enter your key — it stays on your device only

---

## 💡 How to Update
After making changes to any file:
1. Go to your GitHub repository
2. Click on the file you want to update
3. Click the pencil icon (Edit)
4. Make changes & commit

OR use GitHub Desktop app for easier drag-and-drop updates.

---

## 🔒 Privacy Note
All user data is stored in your browser's **localStorage** only.
Nothing is sent to any server. Your data stays on your device.
