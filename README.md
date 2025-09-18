#Fantasy Football Trade Evaluator (Dynasty)

###A learning-first, production-minded web app for dynasty fantasy football trades. Built to be clear (not a black box), configurable to your league, and solid enough that your league mates can actually use it.

###North Star: Ship a transparent, roster-aware dynasty trade evaluator with a clean UI, clear math, and an auditable value breakdown that scales from a personal project to a real portfolio piece employers can evaluate.

##Why this exists

###Most trade calculators are black boxes and/or tuned for redraft. Dynasty value depends on age curves, positional scarcity, league format (e.g., Superflex, TE premium), and whether you’re contending or rebuilding. This app aims to:

###Be dynasty-native (age, windows, picks matter).

###Explain every verdict (no mystery numbers).

###Adapt to your league & roster (context-aware, not generic).

##Flagship differentiators 

###Roster‑Aware Dynasty Value Engine

###Inputs: league settings (Superflex, TE premium, roster/starting slots) + your roster profile (average age, positional depth) + your window (Contend ↔ Rebuild slider).

###Output: a value for each side that blends Projected Production (next 1–2 seasons) with Long‑Term Value (age curve + market).

###Why it’s unique: most calculators ignore your roster context and window.

##Transparent Value Breakdown (“Why?” Panel)

###For every player/pick, show the components:
• Market (ADP/consensus)
• Production (role/snap share proxy, later projections)
• Age Curve (dynasty window)
• Scarcity (replacement-level at position)

###Users can see how the verdict was reached and tweak assumptions live.

###Stretch goals: Draft‑class pick curves by year, injury‑risk toggles, “what‑if” scenarios, and sync with Sleeper league settings (manual first, API later).

##Project status

✅ Next.js app scaffolded (TypeScript, App Router).

🟨 MVP evaluator (UI → API → simple logic) — Next task.

⬜ Prisma + SQLite schema for Player/Pick + seed script.

⬜ Transparent breakdown UI.

⬜ League settings form (SF/TEP/roster sizes) + window slider.

⬜ Deploy to Vercel + (later) Postgres/Neon.