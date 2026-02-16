# Mission Control Dashboard

A unified dashboard for Lindy Assistant settings and Community Manager.

## Features

- 💿**Glassmorphism Design**: Modern, sleek UI with blurred glass effects
- 🌆**Dark/Light Mode**: Toggle between themes with persistent preferences
- ⚙**Lindy Settings**: Manage email, meetings, and SMS settings
- 👥**Community Manager**: Track and manage multiple communities
- 📊**Analytics**: Visualize engagement metrics with Chart.js
- 📦**Supabase Integration**: Real-time settings sync across devices

## Tech Stack

- **Frontend**: Vanilla HTML/CSS/JavaScript
- **Database**: Supabase
- **Charts**: Chart.js
- **Icons**: Font Awesome
- **Hosting**: Vercel

## Deployment

### Deploy to Vercel

1. Connect this repository to Vercel:
   - Go to [Vercel](https://vercel.com/new)
   - Import this GitHub repository
   - Click **Deploy**

2. Your dashboard will be live at: `https://mission-control-dashboard.vercel.app`

## Supabase Setup

The dashboard connects to Supabase for settings storage. The connection details are already configured in `index.html`.

## Local Development

Simply open `index.html` in your browser, or run a local server:

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Features Overview

### Lindy Settings

- **Email Settings**: Triaging, SMS alerts, drafting
- **Meeting Settings**: Scheduling, recording, prepping
- **Text & SMS**: Daily briefs, alerts

### Community Manager

- View all your communities in one place
- Track followers, posts, and engagement
- Manage community status (active/paused)

### Content Vault

- Centralized storage for all your content
- Upload and manage media assets

### Analytics

- Visual engagement tracking
- Weekly performance metrics

## Customization

All settings are stored in Supabase and sync in real-time. Toggle any setting and it will be saved automatically.

## License

MIT License

---

Built with ❤️ by Lindy Assistant