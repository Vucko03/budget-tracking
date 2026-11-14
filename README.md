# Budget Max: install on your phone

Budget Max is a small offline app for logging what you buy each day and seeing reports on where your money goes.
Your data is stored only on your phone. It needs no account and no internet once it is installed.

## What's in this folder
index.html (the whole app), sw.js (makes it work offline), manifest.webmanifest and the icons (make it installable).
Keep all the files together.

## Step 1: put it online once (free)
A phone can only install a web app from an https address, so the files have to be hosted somewhere one time.
After you install it, the app works offline and the data never leaves the phone.

**Option A: GitHub Pages (recommended, free, permanent)**
1. On github.com, create a new **public** repository, e.g. `budget-max`.
2. Click "uploading an existing file" and drag in all the files from this folder. Commit.
3. Go to Settings → Pages → Source: "Deploy from a branch", Branch: `main` / root → Save.
4. After about a minute your app is at `https://<your-username>.github.io/budget-max/`.
(Or tell Claude the repo name and it can upload the files and turn Pages on for you.)

**Option B: Netlify Drop**
Open https://app.netlify.com/drop on a computer, drag this folder in, and sign up (free) so the site doesn't expire.

## Step 2: install on the phone
- **Android (Chrome):** open the link → menu ⋮ → "Install app" / "Add to Home screen". (Or Settings tab → "Install on this phone".)
- **iPhone (Safari):** open the link → Share button → "Add to Home Screen".

Open it once while online so it saves itself for offline use. From then on it works in airplane mode.

## Tips
- Budget tab (first screen): enter your salary each month and split it into parts (vacation, investing, spending…).
- When adding a purchase, the type is 💸 Spending by default. Switch it to 📈 Investing for things like an AI subscription, a course or stocks. Investing entries count toward the budget part marked "Investing", not your spending, and Reports has a Spending / Investing / Both switch.
- Change the currency in Settings (default RSD).
- Use Settings → "Save backup file" once in a while. Use "Restore from backup" on a new phone.
- Reports → empty state has "Try it with sample data" to preview the charts. Remove it in Settings.
