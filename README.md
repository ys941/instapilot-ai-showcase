<div align="center">

<br />

# 🚀 InstaPilot AI

### Your entire content team for **Instagram + YouTube** — automated, for *any* niche

**One AI brain. Two platforms. _Zero daily effort._**

Posts, carousels, Stories, Shorts, Reels, comments, DMs — all on autopilot.

<br />

<p>
  <img alt="Next.js 16" src="https://img.shields.io/badge/Next.js-16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img alt="React 18" src="https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript 5" src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="PostgreSQL + Prisma" src="https://img.shields.io/badge/Postgres-Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img alt="Grok + Gemini" src="https://img.shields.io/badge/AI-Grok%20%2B%20Gemini-7C3AED?style=for-the-badge&logo=google&logoColor=white" />
</p>
<p>
  <img alt="Instagram Graph API" src="https://img.shields.io/badge/Instagram-Graph%20API-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  <img alt="YouTube Data API v3" src="https://img.shields.io/badge/YouTube-Data%20API%20v3-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  <img alt="Docker ready" src="https://img.shields.io/badge/Docker-ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<a href="https://railway.com/new"><img src="https://railway.com/button.svg" alt="Deploy on Railway" height="44" /></a>

<br />
<br />

<kbd>📱 Instagram</kbd> &nbsp; <kbd>▶️ YouTube</kbd> &nbsp; <kbd>🎨 White-label</kbd> &nbsp; <kbd>🏢 Multi-account</kbd> &nbsp; <kbd>🔑 Self-hosted</kbd>

</div>

<br />

---

<div align="center">

## 🎯 Two full-time content jobs → **one app you control**

</div>

Running a serious Instagram **and** YouTube presence is two full-time jobs: ideate, write, design, render, schedule, cross-post — then answer every comment and DM. Every day, on both platforms, forever.

**InstaPilot AI collapses all of it into one app.** It writes the content, designs the visuals, builds the videos, publishes to both platforms on your schedule, cross-posts Shorts to Reels, and replies to your audience — including **voice-note DMs** — in a niche and voice you choose, on accounts that are entirely yours.

<br />

---

## ✨ Why it's different

<table>
<tr>
<td width="50%" valign="top">

### 📱 + ▶️ Two platforms, one brain
Native IG posts, carousels & Stories **and** vertical YouTube Shorts — written once, published everywhere, with identical rich captions.

</td>
<td width="50%" valign="top">

### 🔁 Smart cross-posting
Turn a YouTube Short into an Instagram Reel automatically — same render, on its own deferred schedule.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Real conversations
Auto-replies to IG comments & DMs — even **voice notes → transcribed → spoken reply** — and YouTube comments, in your voice, never to itself.

</td>
<td width="50%" valign="top">

### 🎨 White-label, zero code
App name, niche, persona, handles, content labels — and **10 built-in dashboard themes** — all from the **Settings UI**. Re-skin for any niche in minutes.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 Three AI brains, never stalls
**Grok · Gemini · Cerebras** with **per-task fallback chains** — pick a provider, model, and backups for content, replies, and vision separately, so a single outage never stops your content.

</td>
<td width="50%" valign="top">

### 🏢 Run a whole network
Many paired Instagram + YouTube brands from one dashboard, each fully independent.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ AI voiceover + auto-translated captions
Narrate every Short with a natural AI voice — **perfectly synced to each card** — over auto-ducked music, and let YouTube **auto-translate captions** into every viewer's language, or burn in word-by-word captions. Go global, hands-free.

</td>
<td width="50%" valign="top">

### 🛡️ Built to never miss a beat
Single-flight render lock, JSON-resilient AI fallbacks, and self-healing claim-locks keep posts flowing without duplicates or downtime.

</td>
</tr>
</table>

<br />

---

## 🎬 What happens every day — automatically

> For each brand (a paired Instagram + YouTube account), on the schedule you set:

| | Step | What the AI does |
|:--:|---|---|
| 🧪 | **Invents topics** | From your list, auto-expanded by AI so content never repeats |
| ✍️ | **Writes the content** | Hooks, body, CTA, hashtags — in your niche and voice, with **quality-gated titles** and enforced topic de-dup |
| 🎨 | **Designs the visuals** | Branded image cards, multi-image carousels, and a daily Story |
| 🎞️ | **Builds the Shorts** | Vertical multi-slide videos at a **length you pick (15–60s)**, with mood-matched music, AI search tags, and optional AI voiceover + auto-translated captions |
| 📤 | **Publishes everywhere** | Native IG posts/carousels/Stories + YouTube Shorts, on a per-weekday schedule |
| 🔁 | **Cross-posts** | Shorts become Instagram Reels on their own timing, and optionally native **Facebook Page Reels** too (opt-in) |
| 💬 | **Engages** | Instant replies to IG comments & DMs (incl. voice) and YouTube comments |
| 📊 | **Reports** | Syncs analytics for both platforms and emails a daily digest |

<div align="center"><sub>You mostly just watch the dashboard.</sub></div>

<br />

---

## 🧠 Architecture at a glance

> A single, self-healing automation loop runs your entire content operation — no external cron, no queues, no babysitting.

```
  ┌──────────────────────── In-process engine (every ~5 min, per brand) ─────────────────────┐
  │                                                                                            │
  │  runCatchup()  ──▶  for each ACTIVE brand (own credentials · own brand skin · own plan):    │
  │                       ├─ 📸 generate today's IG posts / carousels / Story                   │
  │                       ├─ 🎬 generate today's YouTube Shorts                                 │
  │                       ├─ 📤 publish everything due  →  IG  ·  YouTube  ·  cross-posted Reel  │
  │                       ├─ 💬 reply to IG comments + DMs (text & voice)                        │
  │                       └─ 💬 reply to YouTube comments (never to itself)                      │
  │                                                                                            │
  │  Webhooks  ──▶  instant comment / DM replies        Daily timer  ──▶  health digest email   │
  └──────────────────────────────────────────────────────────────────────────────────────────┘
```

<table>
<tr>
<td align="center" width="33%"><b>🏢 Multi-tenant</b><br/><sub>Every brand runs the full pipeline independently with isolated data.</sub></td>
<td align="center" width="33%"><b>⚡ Real-time + resilient</b><br/><sub>Webhooks deliver instant replies, with a polling fallback so nothing is missed.</sub></td>
<td align="center" width="33%"><b>🛡️ Self-healing</b><br/><sub>Claim-locks stop double-posts; a reaper + ffmpeg watchdog guard every job.</sub></td>
</tr>
</table>

<br />

---

## 🎥 How content is made

```
  IDEA ─▶ SCRIPT ─▶ CARDS / CAROUSEL ─▶ (video) SHORT ─▶ CAPTION + TAGS ─▶ PUBLISH ─▶ ENGAGE
  (AI)    (AI)      (Satori + Sharp)    (ffmpeg+music)   (AI, shared)       IG + YT     (AI)
```

Visuals render server-side with **Satori → SVG → Sharp** (container-proof), videos assemble through a hardened **ffmpeg** pipeline, and one rich AI caption is shared byte-for-byte across Instagram and YouTube. Every stage degrades gracefully — **the system never blocks on a single failure.**

<br />

---

## 🧰 Built with

<div align="center">

**Next.js 16** · **React 18** · **TypeScript** · **PostgreSQL + Prisma** · **Grok (Groq Llama-3.3-70B)** · **Google Gemini** · **Cerebras** · **Whisper + Gemini TTS**
**Satori + Sharp** · **ffmpeg** · **Jamendo** · **Cloudinary** · **Instagram Graph API + webhooks** · **Facebook Reels** · **YouTube Data API v3** · **Resend** · **Railway / Docker**

</div>

<br />

---

<div align="center">

## 🚂 Deploy in minutes

<a href="https://railway.com/new"><img src="https://railway.com/button.svg" alt="Deploy on Railway" height="44" /></a>

Railway-ready out of the box — Postgres plugin, auto-migrations, health checks, and ffmpeg/fonts pre-configured.
Or run it anywhere with **`docker compose up`**.

<br />

### One dashboard. Two platforms. Your whole content operation, automated. 🚀

<sub>Bring your own API keys · self-hosted · proprietary</sub>

</div>
