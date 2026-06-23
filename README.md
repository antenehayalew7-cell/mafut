# Mafut Nation - Bar Stock Management System

**Live App:** https://antenehayalew7-cell.github.io/mafut

## Features ✨

- 📊 **Stock Tracking** - Track beer/cider inventory with pack size overrides
- 💰 **Profit Analytics** - Weekly profit calculations with product breakdown
- 📱 **Multi-Device Sync** - Supabase cloud sync across phone/laptop/tablet
- 🔐 **Authentication** - Email signup/signin with Supabase
- 💳 **Credit Tracking** - Customer credit book with running balances
- 🎉 **Comps Management** - Track free drinks (DJ, girls, vibe)
- 💼 **Expenses** - Salary, rent, security, DJ fees
- 📈 **Analytics Dashboard** - Charts, trends, stock value, profit potential
- 📤 **Data Export** - JSON, CSV backup/restore
- 💬 **WhatsApp Integration** - 1-tap customer notifications

## Project Structure

```
D:\my website\
├── index.html          # Single-file PWA (1800+ lines)
├── README.md           # This file
├── .git/               # Git repository
└── .claude/            # Claude internal files
```

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Storage:** Supabase (cloud sync), localStorage (fallback)
- **Auth:** Supabase Auth (email/password)
- **Charts:** Chart.js
- **Hosting:** GitHub Pages (free)

## Getting Started

### Local Development
```bash
cd "D:\my website"
python -m http.server 5500
# Visit http://localhost:5500
```

### Deploy Changes
```bash
git add index.html
git commit -m "Your message"
git push origin main
# Changes live in ~1-2 min on GitHub Pages
```

## Data Flow

1. **Buy** → Record purchases from Ultra Liquors
2. **Count** → Weekly physical stock count
3. **Calculate** → Auto-calculates used/sold/profit
4. **Sync** → All data saves to Supabase + localStorage
5. **Analytics** → View trends, product performance, stock value

## Authentication

- Sign up with email at: https://antenehayalew7-cell.github.io/mafut
- Confirm via email link
- Sign in to access your synced data
- Data syncs across all your devices automatically

## Supabase Setup

- **Project:** dlxifcpcumdkndguyycj
- **URL:** https://dlxifcpcumdkndguyycj.supabase.co
- **Table:** mafut_data (stores all user data)
- **Auth:** Email/password via Supabase Auth

## Known Limitations

- Email confirmation required (check spam folder)
- Rate limiting: 5 signups per hour per email
- Free tier: 1 user, 1GB storage, 50k API calls/month

## Future Ideas

- [ ] Multi-user roles (manager, staff, customer)
- [ ] Pool table & gaming machine tracking
- [ ] SMS notifications
- [ ] Inventory forecasting
- [ ] Supplier comparison
- [ ] Mobile app wrapper
- [ ] Real-time collaboration

## Contact

Email: antenehayalew7@gmail.com
Location: Germiston, South Africa
