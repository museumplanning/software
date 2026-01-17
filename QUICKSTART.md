# QUICKSTART GUIDE

## 3 Ways to Use Museum Scoper

---

## 🌐 Option 1: Browser (Instant - Start Right Now!)

**No installation needed. Works immediately.**

```bash
# 1. Download the files
# 2. Double-click index.html
# 3. You're done!
```

**Pros:**
- ✅ Zero setup
- ✅ Works offline
- ✅ Auto-saves to browser localStorage
- ✅ Export JSON anytime

**Cons:**
- ❌ Data only in one browser
- ❌ Can't access file system directly

**Best for:** Testing, quick start, this week's outreach

---

## 🚀 Option 2: GitHub Pages (Online Access Anywhere)

**Access from any device with internet.**

```bash
# 1. Create GitHub account (if needed)
# 2. Create new repository: "museum-scoper"
# 3. Upload all files from museum-scoper-app/
# 4. Go to Settings → Pages
# 5. Enable Pages from "main" branch
# 6. Visit: yourusername.github.io/museum-scoper
```

**Pros:**
- ✅ Access anywhere (phone, tablet, laptop)
- ✅ Version control (Git tracks all changes)
- ✅ Share with team
- ✅ Automatic backups

**Cons:**
- ❌ Requires internet
- ❌ Public repository (or pay for private)

**Best for:** Working from multiple locations, collaboration

---

## 💻 Option 3: Electron Desktop App (Full Power)

**Native desktop application with file system access.**

```bash
# 1. Install Node.js from nodejs.org

# 2. Navigate to project folder
cd museum-scoper-app/

# 3. Install dependencies
npm install

# 4. Run the app
npm start

# 5. (Optional) Build installer
npm run build
```

**Pros:**
- ✅ Works 100% offline
- ✅ Direct file system access
- ✅ Native app feel
- ✅ Can create .exe/.dmg installers
- ✅ Keyboard shortcuts
- ✅ Menu bar integration

**Cons:**
- ❌ Requires Node.js installation
- ❌ 300MB+ with dependencies

**Best for:** Daily use, full-featured workflow, eventual sale

---

## 📊 What's Included

### Data Files (12 Projects)
```
data/
├── discovery-center-v2.json          # Failed - Dir of Development
├── african-american-museum-v2.json   # Failed - Budget mismatch  
├── anrm-arizona-v2.json              # In limbo - Scandal
├── copolk-mcdonough-v2.json          # SUCCESS - Built!
├── cranbrook-strategic-plan-v2.json  # Pending - Fast RFP
├── howard-museum-v2.json             # Declined - Illegal specimens
├── mcdonough-cultural-plan-v2.json   # SUCCESS - Expansion
├── mcdonough-funding-proposal-v2.json
├── macon-digital-experiences-v2.json
├── nature-conservation-cabela-v2.json # Declined - Impossible
├── poughkeepsie-art-center-v2.json
└── convergence-era-v2.json
```

### 30-City Target List
Pre-loaded with:
- City names
- Population data
- SPLOST status
- Historic buildings
- Tier rankings (1-5)

### Email Templates
3 AB-tested versions:
- Version A: McDonough Direct
- Version B: Problem/Solution
- Version C: Data-Driven

---

## 🎯 First Steps (Today)

### Step 1: Open the App (5 minutes)
```bash
# Browser version:
Double-click index.html

# OR GitHub version:
Visit: yourusername.github.io/museum-scoper

# OR Electron version:
npm install && npm start
```

### Step 2: Explore Database (10 minutes)
1. Click "📁 Database (12)" tab
2. Browse 12 extracted projects
3. Click any project to see details
4. Notice success vs. failed patterns

### Step 3: Check JSON Schema (5 minutes)
1. Click "💻 Raw JSON" tab
2. Click "Show All Projects"
3. Review the data structure
4. See what fields are captured

### Step 4: Generate Your First Email (10 minutes)
1. Click "📧 Outreach" tab
2. Select "Cartersville, GA"
3. Email auto-generates!
4. Click "Copy to Clipboard"
5. You're ready to send

---

## 📈 This Week's Goals

### Monday:
- [x] Open the app
- [ ] Browse all 12 projects
- [ ] Understand the patterns

### Tuesday:
- [ ] Research 5 cities from list
- [ ] Add City Manager names/emails
- [ ] Save progress

### Wednesday:
- [ ] Generate 5 emails
- [ ] Send to City Managers
- [ ] Mark as "Contacted"

### Thursday-Friday:
- [ ] Monitor responses
- [ ] Update statuses
- [ ] Export data to JSON

---

## 🔧 Troubleshooting

**App won't open in browser?**
- Try different browser (Chrome, Firefox)
- Check if JavaScript is enabled
- Right-click → Open With → Browser

**Can't save data?**
- Check browser localStorage settings
- Try exporting to JSON file
- Use GitHub version for cloud storage

**Electron app won't start?**
```bash
# Check Node.js installed:
node --version

# Should show: v18.x.x or higher
# If not, install from nodejs.org

# Clear cache and reinstall:
rm -rf node_modules
npm install
npm start
```

**JSON files not loading?**
- Check `data/` folder exists
- Verify all 12 .json files present
- Make sure file permissions correct

---

## 💡 Pro Tips

### Export Often
```javascript
// Export after every session
Click: 💾 Export All Data (JSON)
Save as: museum-scoper-backup-2026-01-20.json
```

### Use Git Commits
```bash
# After making changes:
git add .
git commit -m "Added City Manager emails for 5 cities"
git push
```

### Keyboard Shortcuts (Electron)
- `Cmd/Ctrl + 1`: Dashboard
- `Cmd/Ctrl + 2`: Projects
- `Cmd/Ctrl + 3`: Cities
- `Cmd/Ctrl + E`: Export
- `Cmd/Ctrl + I`: Import

---

## 🎓 Learning Path

**Week 1:** Use browser version, get comfortable
**Week 2:** Set up GitHub Pages, access anywhere
**Week 3:** Try Electron app, experience full power
**Month 2:** Consider Python/Flask backend
**Month 6:** Full automation with AI

---

## 📞 Need Help?

**Check:**
1. README.md (detailed docs)
2. GitHub Issues (report bugs)
3. Email: mark@museumplanning.com

**Common Questions:**
- "How do I add more projects?" → Edit the JSON files
- "Can I customize email templates?" → Yes, in Templates tab
- "Will this work on iPad?" → Browser version yes, Electron no
- "How to backup?" → Export JSON + commit to GitHub

---

## 🚀 Ready to Start?

```bash
# Pick your path:

# Path 1 (Fastest):
open index.html

# Path 2 (Best):
# Upload to GitHub → Enable Pages → Access online

# Path 3 (Most Powerful):
npm install && npm start
```

**Start with Path 1 today. Upgrade to Path 2-3 when ready.**

You have everything you need to send your first 5 emails this week!
