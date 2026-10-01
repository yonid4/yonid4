<div align="center">

# 👋 Hey, I'm Yoni Dayagi

**Backend Developer · AI Enthusiast · Bay Area, CA**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yoni-dayagi)&nbsp;&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-yonidayagi.com-00FF41?style=for-the-badge)](https://www.yonidayagi.me/)&nbsp;&nbsp;
[![Open to Work](https://img.shields.io/badge/🟢_OPEN_TO_WORK-Backend_/_Full--Stack-2ea44f?style=for-the-badge)](https://linkedin.com/in/yoni-dayagi)

</div>

---

I build tools that save people time — usually by combining **AI** with **practical automation**. I'm currently looking for **full-stack or backend** roles where I can keep doing that.

---

## 🛠️ Tech Stack

<div align="center">

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://docs.python.org/3/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://devdocs.io/javascript/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)](https://nextjs.org/docs)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)](https://docs.claude.com/)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white)](https://ai.google.dev/gemini-api/docs)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)](https://developers.openai.com/api/docs/)
[![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/docs)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)](https://docs.trychroma.com/docs/overview/getting-started)
[![OAuth](https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white)](https://oauth.net/2/)

</div>

---

## 🚀 Featured Projects

### [When](https://github.com/yonid4/when-V2) — Smart Group Scheduling &nbsp; [![LiveSite](https://img.shields.io/badge/Live_Site-Visit-2ea44f?style=flat-square)](https://when-now.com)
> Find the best meeting time across everyone's calendars — without the back-and-forth

- 🗓️ Google Calendar + Microsoft Outlook sync through a shared provider layer: multiple accounts per user, busy slots refreshed hourly by a background scheduler
- 📊 Interactive availability heatmap, plus swipe-to-mark preferred slots so people can show their ideal times, not just their open ones
- 🎯 Ranking algorithm scores candidate times by calendar conflicts & preferred-slot overlap, handles overnight windows, skips past times, and surfaces the top 5
- ⚡ Real-time collaboration via Supabase Realtime: live calendar syncs, RSVPs & proposal updates for every viewer
- 📅 One-click finalize writes the event onto each participant's own calendar with their own provider; people without a connected calendar get an emailed invite
- 🔐 Expired calendar tokens are detected and prompt a reconnect; account deletion revokes OAuth tokens before removing data
- 🧪 Over 280 backend tests (pytest) plus a Vitest frontend suite; Supabase Row Level Security on every table

### [Job Autopilot](https://github.com/yonid4/job-autopilot) — AI Job Search Pipeline
> Finds jobs that fit your resume, tracks them in a Google Sheet, and keeps each application's status up to date from your inbox

- 🤖 **Gemini AI** scores resume-to-job fit (0–100); only jobs ≥ 80 reach the sheet, sorted by score, with company blocklist & API key rotation
- 🔍 Pluggable scrapers: LinkedIn (session-cookie auth) or hiring.cafe (no auth), picked with one setting
- 📬 Gmail tracker classifies recruiting emails (rejection, OA, interview, offer) and updates the matching row automatically
- 🧠 Cheap rules first: a weighted phrase matcher handles most emails, and only unclear ones go to Gemini, in batches
- 🪜 Forward-only status ladder: a late auto-reply can't knock a row back from "Interviewing", and rows you closed yourself are never overwritten
- 🔔 Discord pings for assessments, interviews & offers; runs daily on **GitHub Actions** with a dry-run mode and offline tests

### [Boulder Bay](https://github.com/yonid4/boulder-bay) — Bay Area Climbing Gym Crowd Tracker &nbsp; ![Status](https://img.shields.io/badge/Status-In_Progress-orange?style=flat-square)
> Which bouldering gym should I go to right now? Live crowd levels, best times to climb, and a ranked pick based on where you are

- 📱 Native **SwiftUI** iOS app (MapKit, MVVM with `@Observable`) backed by a **FastAPI** service
- 🗺️ Supabase Postgres + **PostGIS** schema with a hand-verified seed of 16 Bay Area gyms, their hours & rates
- 🔐 Supabase Auth with ES256 JWT verification against the project's JWKS
- 🕷️ Headless Playwright scraper reads Google's popular-times data (live + weekly curve), with retries for flaky page loads
- 🎯 *Planned:* ranking that weighs crowd level, travel time (Mapbox) and your gym memberships, plus a time scrubber to see projected crowds
- ✅ CI on every push: ruff, strict mypy & pytest for the backend, plus `xcodebuild test` for the app

---

## 💼 Experience

**AI Engineer — B2B Construction Tech Startup** *(3 months)*

| What I Did | Impact |
|---|---|
| Built an AI-powered RFP analysis tool | ⏱️ Reduced review time from **2–3 days → under 8 minutes** |
| De-risked development through proactive communication | 🛡️ Prevented **2+ days** of rework |

---

<div align="center">

📫 **Interested in working together?** Connect on [LinkedIn](https://linkedin.com/in/yoni-dayagi) or visit [yonidayagi.com](https://www.yonidayagi.me/)

</div>
