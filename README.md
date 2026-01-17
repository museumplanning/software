# Museum Scoper - McDonough Model Database & City Tracker

**A complete system for targeting cities, tracking outreach, and managing museum planning projects.**

## 🎯 What This Is

**Museum Scoper** combines:
- ✅ **12 Extracted Projects** (JSON database with complete metadata)
- ✅ **30-City Target List** (McDonough Model replication candidates)
- ✅ **Automated Email Generation** (Personalized outreach templates)
- ✅ **Project Tracking** (From initial contact → contract signed)
- ✅ **Pattern Analysis** (Success/failure predictors from real data)

## 📁 Project Structure

```
museum-scoper-app/
├── index.html          # Main application (works in browser)
├── data/               # JSON database (12 projects)
│   ├── discovery-center-v2.json
│   ├── african-american-museum-v2.json
│   ├── anrm-arizona-v2.json
│   ├── copolk-mcdonough-v2.json
│   ├── cranbrook-strategic-plan-v2.json
│   ├── howard-museum-v2.json
│   ├── mcdonough-cultural-plan-v2.json
│   ├── mcdonough-funding-proposal-v2.json
│   ├── macon-digital-experiences-v2.json
│   ├── nature-conservation-cabela-v2.json
│   ├── poughkeepsie-art-center-v2.json
│   └── convergence-era-v2.json
├── docs/               # Documentation
│   ├── 30_CITIES.md
│   └── WORKFLOW.md
├── package.json        # Electron configuration
└── README.md           # This file
```

## 🚀 Quick Start

### Option 1: Use in Browser (Immediate)

1. Download this repository
2. Open `index.html` in your browser
3. Start using immediately - no installation needed!

### Option 2: GitHub Pages (Online Access)

1. Fork this repository
2. Go to Settings → Pages
3. Enable Pages from `main` branch
4. Access at: `yourusername.github.io/museum-scoper`

### Option 3: Electron App (Desktop Application)

```bash
# Install dependencies
npm install

# Run the app
npm start

# Build for distribution
npm run build
```

## 💾 Database Schema

Each project JSON file contains:

```json
{
  "project_id": "unique-identifier",
  "project_name": "Full project name",
  "client": {
    "name": "Client organization",
    "location": { "city": "", "state": "", "country": "" },
    "type": "city_government | museum | university | private",
    "population": 30000
  },
  "decision_makers": {
    "primary_contact": {
      "name": "",
      "role_type": "city_manager | executive_director | etc",
      "authority_level": "final_decision | recommends"
    }
  },
  "project_financials": {
    "your_bid_amount": 300000,
    "payment_status": "paid_in_full",
    "strategic_underbid": false
  },
  "project_outcome": {
    "status": "built_and_operational | failed | pending",
    "why_succeeded": ["factor1", "factor2"],
    "why_failed": ["factor1", "factor2"]
  },
  "ai_training_quality": {
    "confidence_score": 0.95,
    "notes": "Quality assessment for AI training"
  },
  "tags": ["success_story", "city_government", "splost_funded"]
}
```

## 📊 Current Database Stats

- **Total Projects:** 12
- **Success Stories:** 2 (C.O. Polk, McDonough Cultural Plan)
- **Failed Projects:** 4 (Discovery Center, African American, Howard, Cabela)
- **In Progress:** 6 (ANRM, Cranbrook, Poughkeepsie, etc.)

## 🎯 Success Patterns Identified

### ✅ What Works
- **City Manager client** (final authority) = 100% success
- **SPLOST funding** (appropriated, not fundraising) = High success
- **Fast decision** (15-min meeting, 18-day RFP) = Strong signal
- **Historic building** + preservation mandate = External driver
- **Retiring politician** = Deadline pressure

### ❌ What Doesn't Work
- **Director of Development** leading = 0% success
- **Budget 1/5 of needed** = Instant failure
- **Private collector** + family board = Tax shelter (decline)
- **Illegal specimens** = Legal liability (decline)
- **Refused curriculum integration** = Dealbreaker

## 📧 Outreach System

The app auto-generates personalized emails using 3 tested templates:

**Version A:** McDonough Model Direct Comparison
**Version B:** Problem/Solution Framework
**Version C:** Data-Driven (3 metrics)

Simply select a city, choose template, copy email → send!

## 🏙️ 30-City Target List

Cities ranked by probability (Tier 1-5):
- **Tier 1:** Cartersville GA, Thomasville GA, Valdosta GA, Rome GA, Newnan GA
- **Tier 2:** Decatur AL, Florence AL, Gaffney SC, Anderson SC, Rock Hill SC
- **Tier 3:** DeLand FL, Ocala FL, Cookeville TN, Cleveland TN, Columbia TN
- (See full list in app)

## 🔧 Technology Stack

- **Frontend:** HTML5 + CSS3 + Vanilla JavaScript
- **Data Storage:** LocalStorage + JSON files
- **Deployment:** GitHub Pages or Electron
- **Future:** Python/Flask backend for full automation

## 📈 Roadmap

### Phase 1: Manual Validation (Current)
- ✅ JSON database extracted (12 projects)
- ✅ HTML app built
- ✅ 30 cities identified
- ⏳ AB test emails (5 cities)
- ⏳ Validate templates

### Phase 2: Template Automation (Months 3-6)
- AI-generated emails
- Auto-populated proposals
- Pattern matching from database
- Success probability scoring

### Phase 3: Full Automation (Months 6-12)
- Auto-research cities
- Scheduled outreach campaigns
- Response tracking
- Proposal generation from database

## 🎓 Use Cases

1. **City Targeting:** Research and prioritize 30 cities
2. **Outreach Management:** Generate and track emails
3. **Pattern Analysis:** Learn from 12 past projects
4. **Proposal Generation:** Use database comparables
5. **Portfolio Showcase:** Demonstrate methodology
6. **Acquisition Prep:** Document systematic approach

## 💡 AI Training Ready

All JSON files include:
- `ai_training_quality` scores (0.60 - 1.0)
- Success/failure labels
- Complete decision maker data
- Budget and timeline info
- Lessons learned

**Perfect for training Museum Scoper AI to predict project success!**

## 📝 Contributing

This is a private system, but improvements welcome:
1. Additional project extractions
2. Enhanced email templates
3. Better pattern analysis
4. UI/UX improvements

## 🔒 Data Privacy

- No client names in GitHub (use placeholders)
- Generic building names
- Remove sensitive contract terms
- Public version = learning system only

## 📧 Contact

**Mark Walhimer**
- Website: culture-planning.com
- Email: mark@museumplanning.com
- Portfolio: museumplanning.com

---

## 🚀 Get Started Now

```bash
# Clone the repo
git clone https://github.com/yourusername/museum-scoper.git

# Open in browser
open index.html

# Or run as Electron app
npm install && npm start
```

**Start targeting cities this week!**
