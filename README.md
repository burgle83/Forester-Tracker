# Forester Maintenance Tracker — Get It On Your Phone

## The Easiest Way: Netlify Drop (Free, No Account Needed)

### Step 1: Download the app folder
Download the `forester-app.zip` file from this conversation.

### Step 2: Unzip it
Unzip the file on your computer. You should see a folder with these files:
- `index.html`
- `app.jsx`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

### Step 3: Deploy to Netlify (30 seconds)
1. Go to **https://app.netlify.com/drop** in your browser
2. Drag the entire **forester-app** folder onto the page
3. Wait about 10 seconds — it'll give you a URL like `https://random-name-12345.netlify.app`
4. That's it! Your app is live on the internet.

### Step 4: Add to your phone's home screen

**iPhone:**
1. Open the URL in Safari (must be Safari, not Chrome)
2. Tap the Share button (square with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"**
5. The app icon appears on your home screen — opens full-screen like a real app!

**Android:**
1. Open the URL in Chrome
2. Tap the three-dot menu (⋮) in the top right
3. Tap **"Add to Home screen"** or **"Install app"**
4. Tap **"Add"**
5. The app icon appears on your home screen!

---

## Optional: Get a custom URL

After deploying to Netlify:
1. Click "Set up your site" on the Netlify page
2. Create a free account (just email)
3. Go to **Site settings → Domain management → Custom domain**
4. Change the random name to something like `forester-tracker.netlify.app`

---

## Your Data Is Safe

All your maintenance logs, vehicle info, receipts, and settings are saved in your phone's browser storage (localStorage). This means:
- ✅ Your data stays on YOUR phone
- ✅ Works offline after first load
- ✅ No account or login needed
- ✅ Nobody else can see your data
- ⚠️ If you clear your browser data, your logs will be erased
- 💡 Tip: Periodically screenshot your log page as a backup

---

## Updating the App

If you get a new version from Claude:
1. Download the new files
2. Go to https://app.netlify.com (log in if you made an account)
3. Go to your site → Deploys → drag the new folder to deploy
4. Your phone will pick up the update next time you open the app

---

## Troubleshooting

**"Add to Home Screen" not showing?**
- iPhone: Must use Safari, not Chrome or Firefox
- Android: Must use Chrome
- Make sure you're visiting the https:// URL (not http://)

**App looks weird on phone?**
- Try closing and reopening it from the home screen icon
- Clear the site data and reload once

**Lost my data?**
- Unfortunately, localStorage data can't be recovered if cleared
- This is why receipt photos are saved — they're your backup!
