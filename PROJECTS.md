# Project Portfolio
*Last updated: 2026-03-25 — Update this date and progress bars each session.*

---

## EMDR Therapy Session Manager
**Started:** 2026-03-23 · **Days active:** 2
**Status:** 🟢 Active
**Progress:** No formal checklist yet — actively being built
```
[░░░░░░░░░░░░░░░░░░░░] ~15%  (foundation built, features in progress)
```
**Overview:** A Phoenix/LiveView web app for EMDR therapists to run real-time therapy sessions. Therapist controls a moving ball (bilateral stimulation), bilateral audio, and Joy-Con haptic feedback from a dashboard. Client joins via a human-readable session token (e.g. `calm-ocean-seahorse-428`). Sessions are HIPAA-conscious with no PII stored.

**Audience:** Licensed EMDR therapists + their clients.

**Revenue potential:** SaaS subscription per therapist. Strong niche — few digital tools exist for this. Therapists pay well for purpose-built tools. High recurring revenue potential.

**Stack:** Elixir/Phoenix · LiveView · PubSub · WebHID (Joy-Con) · Postgres · HTTPS (self-signed cert, IP SAN)

---

## IFS Parts Mapper
**Started:** 2026-03-24 · **Days active:** 1
**Status:** 🟡 Planning
**Progress:** 0 of 7 tasks complete
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** A Phoenix/LiveView app that lets users visually map their Internal Family Systems (IFS) therapy parts as an interactive node/link graph. Each node is a part (Exile, Manager, Firefighter, Self) with details viewable in a side panel. Users can export a printable PDF report to share with their therapist.

**Audience:** Individuals doing IFS therapy or self-directed internal work. Therapists could use it with clients.

**Revenue potential:** Low-cost subscription or one-time purchase. Niche but passionate audience. Therapy-adjacent apps see strong word-of-mouth. Potential therapist licensing tier.

**Stack:** Elixir/Phoenix · LiveView · Cytoscape.js (graph rendering) · PDF export

---

## Pill (Medication Schedule App)
**Started:** 2026-03-24 · **Days active:** 1
**Status:** 🟡 Planning
**Progress:** 0 of 12 tasks complete (8 MVP + 4 Phase 2)
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** A hyper-specific medication reminder app for alternating two pills on custom intervals with a variable daily start time and a hard nighttime cutoff. Solves what 13 other apps (including Pillo) failed to do. Built as a Phoenix PWA wrapped in a native Android APK via Capacitor — no Android code required.

**Audience:** Initially personal use. Broader market: chronic pain patients with specific alternating medication schedules.

**Revenue potential:** Personal tool first. If opened to others — low-cost subscription or one-time purchase. Underserved niche (most pill apps are too generic). Potential partnership with pain management clinics.

**Stack:** Elixir/Phoenix · LiveView · Capacitor (Android APK) · Web Push notifications · SQLite/Postgres · Fly.io or friend's server

---

## Silence (Classroom Noise Monitor)
**Started:** 2026-03-24 · **Days active:** 1
**Status:** 🟡 Planning
**Progress:** 0 of 19 tasks complete (across 4 phases)
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** A plug-and-play HDMI device (Raspberry Pi CM4 + custom PCB) that monitors classroom noise and displays a gamified candy jar reward on the TV. Green = jar fills slowly. Yellow = jar pauses. Red = jar depletes. Teacher controls it from their phone. Device creates its own 802.11s mesh network — zero school IT involvement. Teacher's phone acts as the internet bridge for OTA updates. Subscription model delivers monthly content packs (seasonal themes, national leaderboards).

**Audience:** K-12 teachers and schools. Sells to individual teachers or at the school/district level.

**Revenue potential:** Hardware ~$45-60 one-time. Subscription tiers: Free / $79/yr / $149/yr per school. Long-term revenue from monthly content packs + national leaderboard participation. High appeal to EdTech buyers. Strong word-of-mouth between teachers.

**Stack:** Nerves (Elixir embedded) · Phoenix LiveView · NervesHub (OTA) · 802.11s mesh · Raspberry Pi CM4 · PCBWay custom carrier board + enclosure

---

## Security Auditor
**Started:** 2026-03-21 · **Days active:** 4
**Status:** 🟡 Planning
**Progress:** 0 of 7 tasks complete
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** A Phoenix web app paired with a Raspberry Pi audit node (running Kali Linux). Torey deploys the Pi to a client's network; it auto-scans using nmap, hping3, nikto, and aircrack-ng, then reports findings back to the Phoenix app which generates clean PDF reports. Tunneled securely via Tailscale mesh VPN — no port forwarding needed.

**Audience:** Small-to-mid-size businesses needing network security audits. Torey's consulting clients.

**Revenue potential:** Billable consulting hours per audit. Report as a deliverable adds perceived value. Scalable — one Pi per client engagement. Future: license the app to other security consultants.

**Stack:** Elixir/Phoenix · Kali Linux ARM (Pi) · nmap/nikto/aircrack-ng · Tailscale (VPN) · PDF generation · NervesHub (future)

---

## Social (Cross-Platform Social Poster)
**Started:** 2026-03-19 · **Days active:** 6
**Status:** 🟢 Active
**Progress:** No formal checklist found — architecture phase
```
[░░░░░░░░░░░░░░░░░░░░] ~10%  (Phoenix app created, auth built)
```
**Overview:** Write or upload once, post everywhere. A privacy-first social media automation tool for regular individuals (not businesses). Tag a post for which platforms to send it to, and it distributes automatically. Designed to undercut tools like Postfity ($20-400/mo) which target businesses and harvest user data.

**Audience:** Everyday people with personal social accounts. Content creators who want multi-platform presence without paying business SaaS prices.

**Revenue potential:** Free or very low-cost tier. Revenue via optional premium features (scheduling, analytics, more platforms). Privacy-first positioning is the differentiator in a crowded market. Large total addressable market.

**Stack:** Elixir/Phoenix · PostgreSQL · n8n (social media automation layer) · Magic link auth

---

## Teagles Consulting Website
**Started:** 2026-03-19 · **Days active:** 6
**Status:** 🟡 In Progress
**Progress:** 0 of 16 tasks complete (across 3 phases)
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** Rebuilding the Teagles Consulting website (teaglesconsulting.com) from a single page to a full multi-page Phoenix site. Showcases services including ShopFlow (job shop SaaS), LaborTracker (10+ years in production), custom software, document scanning, QuickBooks help, and AI adoption. Blog and case studies in later phases.

**Audience:** Small manufacturing and custom fabrication businesses (1-15 person shops). Shop owners who need software or operational help.

**Revenue potential:** Marketing/lead generation for existing consulting services. Drives inbound leads for ShopFlow and LaborTracker SaaS products (recurring revenue).

**Stack:** Elixir/Phoenix · HEEx templates · Markdown (blog) · JSON (dynamic data) · No database needed

---

## Mileage Tracker
**Started:** 2026-03-17 · **Days active:** 8
**Status:** 🟢 Active
**Progress:** 13 of 25 tasks complete
```
[██████████░░░░░░░░░░] 52%
```
**Overview:** A privacy-first Phoenix/LiveView app for tracking IRS business mileage deductions. Upload Google Maps Timeline data, categorize trips as business/personal, adjust mileage, reconcile records, and export IRS-compatible CSV and PDF reports. No data is stored persistently — everything lives in the session.

**Audience:** Self-employed individuals, freelancers, and specific employees (armed forces reservists, performing artists, government officials) who deduct mileage on Schedule C.

**Revenue potential:** Could launch as a free tool or low-cost SaaS ($4-9/mo). Strong seasonal demand around tax time. Privacy-first angle differentiates from Google/Intuit alternatives.

**Stack:** Elixir/Phoenix · LiveView · Google Maps Timeline JSON parsing · Geocoding API · PDF/CSV export · Session-only storage

---

## Spotlight Theater (Torey)
**Started:** 2026-02-01 · **Days active:** 52
**Status:** 🔴 Paused / Pending Build
**Progress:** 0 of ~20 tasks complete (phases 1-5 not started)
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** A Phoenix web app for Spotlight Theater — a non-profit homeschool community theater in West Michigan. Public pages display upcoming productions with photos and ticketing links. Admin system lets Debbie and her team manage productions, schedule performances, upload photos (Cloudflare R2), and generate reports. Magic link login only — no passwords.

**Audience:** Theater patrons (public site) + internal admin team (Debbie + ~2 staff).

**Revenue potential:** Non-profit tool — revenue not the goal. Potential future: ticketing integration. Could be packaged and sold to other small community theaters.

**Stack:** Elixir/Phoenix 1.8 · LiveView · PostgreSQL · Cloudflare R2 (image storage) · Magic link auth · Capistrano deploy to teagles.io

---

## Verdancy (Visual Novel Platform)
**Started:** 2026-03-22 · **Days active:** 3
**Status:** 🟡 Planning
**Progress:** 0 of 8 tasks complete
```
[░░░░░░░░░░░░░░░░░░░░] 0%
```
**Overview:** A web-based visual novel platform hosting a trilogy of sci-fi stories whose titles spell V-E-R-D-A-N-C-Y (VeR, Dan, Cy). Users subscribe or purchase per-book to read branching stories with multiple endings. The same story data exports to Ren'Py format for a future Steam/desktop version. Character art via Leonardo AI for consistency, backgrounds via Gemini. Copyright registration before publishing.

**Audience:** Visual novel readers, sci-fi fans, indie fiction readers. Potential crossover to Steam gaming audience via Ren'Py export.

**Revenue potential:** Subscription (monthly, all three books) + per-book purchase via Stripe. Future: Steam sales via Ren'Py, Amazon KDP for ebook/print-on-demand. Strong long-tail revenue if trilogy completes.

**Stack:** Elixir/Phoenix · LiveView · Stripe (subscription + one-time) · Custom story schema · Ren'Py export · Leonardo AI / Gemini (art generation)

---

*Progress bars calculated from checklist items in dev/plans and dev/notes files. Update percentages as tasks complete.*
*To update: edit the bar and percentage manually, or ask a Clauderling to re-scan and recalculate.*
