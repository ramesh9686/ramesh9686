# Ramesh G R (`ramesh9686`) — GitHub Profile README Setup & Customization Guide

This guide explains the architecture and services powering your GitHub profile README, including WakaTime metrics, GitHub telemetry cards, animated calligraphy signature, and dark modern / cyberpunk assets.

---

## 📑 Table of Contents

1. [WakaTime Activity Automation](#-wakatime-activity-automation)
2. [GitHub Telemetry & Stats Cards](#-github-telemetry--stats-cards)
3. [Cyberpunk Assets & Animated Graphics](#-cyberpunk-assets--animated-graphics)
4. [Portfolio & Social Links](#-portfolio--social-links)
5. [Maintenance & Routine Updates](#-maintenance--routine-updates)

---

## ⏱️ WakaTime Activity Automation

The profile includes automatic WakaTime coding telemetry to display your programming language distribution and coding activity.

### Setup Instructions

1. **Get your WakaTime API Key**:
   - Log in to your account at [wakatime.com](https://wakatime.com)
   - Navigate to [Account Settings → API Key](https://wakatime.com/settings/api-key)
   - Copy your secret API key.

2. **Generate GitHub Personal Access Token (PAT)**:
   - Go to [GitHub Settings → Developer Settings → Personal Access Tokens (Classic)](https://github.com/settings/tokens)
   - Generate a new token with `repo` scope permissions.
   - Copy the generated token string.

3. **Add Repository Secrets**:
   - Navigate to this repository: `https://github.com/ramesh9686/ramesh9686/settings/secrets/actions`
   - Click **"New repository secret"** and add:
     - `WAKATIME_API_KEY`: *(Your WakaTime API Key)*
     - `GH_TOKEN`: *(Your GitHub Personal Access Token)*

4. **Verify GitHub Actions Workflow**:
   - The workflow file is configured at `.github/workflows/update-timestats.yml`.
   - It runs automatically every night at midnight UTC or can be manually triggered via the **Actions** tab by selecting **"WakaTime Dev Metrics"** → **"Run workflow"**.

---

## 📈 GitHub Telemetry & Stats Cards

The profile features 4 synchronized cards styled with custom hex parameters to match the `#07090e` dark cyberpunk theme:

- **Overall Stats Card**:
  `https://github-readme-stats.vercel.app/api?username=ramesh9686&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&bg_color=07090e&title_color=6366f1&text_color=94a3b8&icon_color=10b981&border_color=1e293b`

- **GitHub Streak Card**:
  `https://github-readme-streak-stats.herokuapp.com/?user=ramesh9686&theme=dark&background=07090e&border=1e293b&stroke=1e293b&ring=6366f1&fire=10b981&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=6366f1&sideLabels=94a3b8&dates=64748b`

- **Top Languages Card**:
  `https://github-readme-stats.vercel.app/api/top-langs/?username=ramesh9686&layout=compact&theme=tokyonight&bg_color=07090e&title_color=6366f1&text_color=94a3b8&border_color=1e293b`

- **WakaTime Weekly Card**:
  `https://github-readme-stats.vercel.app/api/wakatime?username=ramesh9686&theme=tokyonight&bg_color=07090e&title_color=6366f1&text_color=94a3b8&icon_color=10b981&border_color=1e293b&layout=compact`

---

## 🎨 Cyberpunk Assets & Animated Graphics

Located in the [`assets/`](file:///c:/Users/Lenovo/Documents/ramesh9686/assets) directory:

- **`header-banner.svg`**:
  Vector cyberpunk banner with glowing radial atmosphere (#6366f1 indigo and #10b981 emerald), live telemetry readout, animated pulse indicator, and personal branding for Ramesh G R.
- **`signature.svg`**:
  Animated calligraphy cursive signature for "Ramesh G R" with glowing path rendering and metadata caption.
- **`divider.svg`**:
  Cyberpunk neon linear gradient divider with central nodes.
- **Typing Headline**:
  Powered by `readme-typing-svg` cycling through:
  `"Data Engineer" | "Python Developer" | "ETL Pipeline Architect" | "Data Analytics Specialist"`.

---

## 🌐 Portfolio & Social Links

| Platform | Destination URL |
| :--- | :--- |
| **Interactive Portfolio** | [https://ramesh13.online](https://ramesh13.online) (Mirror: [Render Deployment](https://ramesh-portfolio-sh4i.onrender.com)) |
| **LinkedIn** | [linkedin.com/in/ramesh-radhakrishnan-a1517a19a/](https://www.linkedin.com/in/ramesh-radhakrishnan-a1517a19a/) |
| **Direct Email** | [grrameshyamini13@gmail.com](mailto:grrameshyamini13@gmail.com) |
| **Resume (Google Drive)** | [View CV](https://drive.google.com/file/d/1JvWT49gFLIWxs67gSm-7QlFii-XSxmKa/view?usp=sharing) |
| **GitHub Sponsors** | [github.com/sponsors/ramesh9686](https://github.com/sponsors/ramesh9686/) |
| **Instagram** | [instagram.com/dynamo._13/](https://www.instagram.com/dynamo._13/) |
