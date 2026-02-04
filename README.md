# SEAL Dashboard

A comprehensive analytics dashboard for tracking Strategic Executive Advisor & Luminary (SEAL) program performance with live Airtable integration.

## Features

- 📊 **Executive Summary** - Key metrics and FY27 goal progress
- 💰 **Pipeline Tracking** - Influenced and closed won opportunities
- 👥 **SEAL Performance** - Individual advisor metrics and leaderboards
- 📈 **Historical Progression** - Quarterly ACV breakdown with true historical snapshots
- 🎯 **Strategic Events** - Event/webinar tracking and completion
- 🔄 **Live Data** - Connects directly to Airtable with embedded read-only token

## Quick Start

### Option 1: Pre-configured Link (Easiest)
If you received a link with `?token=` in it, just click it! The dashboard will auto-configure and load live data immediately.

### Option 2: Manual Configuration
1. Visit: https://lisahanna-a11y.github.io/seal-dashboard/
2. Click **Settings** (⚙️ icon in top right)
3. Paste the shared read-only Airtable token (provided by your team lead)
4. Click **Connect to Airtable**
5. Dashboard loads with live data!

**Note:** Your token is stored locally in your browser and never shared.

## Filters

- **Date Range**: FY27, FY26, This Quarter, Last Quarter, YTD, and more
- **SEAL Filter**: Isolate individual SEAL performance

## Data Source

Connected to BetterUp's SEAL Reporting Airtable base with the following tables:
- Opportunities
- Requests
- Confirmed Engagements
- SEALs

## Technical Details

- Single-page HTML dashboard
- Client-side JavaScript (no server required)
- Airtable Personal Access Token stored in browser localStorage
- Responsive design with Tailwind CSS
- No backend or database needed

## Updating

To update the dashboard, edit `index.html` and commit/push changes. GitHub Pages will automatically deploy updates.

---

Built with ❤️ for the BetterUp SEAL team
