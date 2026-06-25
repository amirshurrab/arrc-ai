# ARRC × LGN — AI Enablement Hub

A set of self-contained, branded HTML pages showcasing AI capabilities for **ARRC** (Arrab United for Consulting and Digital Solutions), in partnership with **London Gulf Nexus (LGN)**.

Open **`index.html`** (or `ARRC-AI-Hub.html`) to start. Everything is static — no build step, no server required.

## Pages
| File | What it is |
|------|------------|
| `ARRC-AI-Hub.html` | Master hub linking everything |
| `ARRC-Claude-Agentic-Tour.html` | Agentic capability tour (interactive) |
| `ARRC-Claude-Demo.html` | Beginner AI capability demo (interactive) |
| `ARRC-AI-Prompts.html` | Copy-ready prompt library (Claude / Gamma / NotebookLM) |
| `ARRC-AI-Toolkit.html` | 23 curated AI tools |
| `ARRC-Whats-Next.html` | Adoption roadmap + ISO/IEC 42001 service line |
| `ARRC-LGN-Solutions.html` | LGN AI learning solutions suite |
| `ARRC-Survey-Form.html` | Seminar satisfaction survey → exports to Excel |
| `arrc-logo.svg`, `survey-qr.png` | Brand + QR assets |
| `Seminar-Survey-Responses-TEMPLATE.xlsx` | Blank responses sheet |

## Deploy (easiest options)

**Option A — Netlify Drop (fastest, no account needed to preview):**
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. You get a live URL in seconds (e.g. `https://random-name.netlify.app`).

**Option B — GitHub Pages (you have GitHub):**
1. Create a new public repo, e.g. `arrc-ai`.
2. Upload all files in this folder (drag-and-drop in the GitHub web UI works).
3. Repo **Settings → Pages → Source: Deploy from a branch → `main` / root → Save**.
4. Live at `https://YOUR-USERNAME.github.io/arrc-ai/` (loads the hub via `index.html`).

## Survey responses — important
A static site can't store form submissions on a server. The survey works two ways:
- **Kiosk mode (works now):** responses are saved in the browser on the device and exported to Excel from the form's *Organiser tools* panel. Great for a tablet at the event.
- **Multi-device via QR:** set a free collection endpoint (Formspree or a Google Apps Script web app) in `const ENDPOINT` near the top of the `<script>` in `ARRC-Survey-Form.html`, so every phone's submission lands in one central sheet.

LGN brand assets © London Gulf Nexus. UPGRADEjourney™ is a registered trademark of London Gulf Nexus.
