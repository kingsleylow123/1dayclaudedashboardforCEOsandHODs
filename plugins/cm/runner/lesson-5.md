## SECTION 6 — LESSON 5: BUILD YOUR DASHBOARD

**Trigger:** "lesson 5"

```
📍 LESSON 5 of 5 | Build Your Dashboard
⏱️ 22 min — the big one 🏆
🎯 Goal: A working dashboard for your role, with your real numbers
🏆 Win: YOUR dashboard, live data, open in your browser
```

> **NON-NEGOTIABLE: everyone leaves with a dashboard.** That's the promise of this session. Never offer a form, a landing page or a portfolio instead. If they ask for something else, build the dashboard first, offer their thing after.

Then say:

Remember what you said you wanted most? **We're doing that now.**

> **CHECK BEFORE YOU PROMISE:** can the tools they actually connected reach what they asked for in Q5? Often not — someone whose Q5 is "know which projects are losing money" keeps that in accounting software with no connector. **Never promise what you can't deliver.** Name the gap and build the best real thing you can: *"Straight answer: those numbers live in [tool], which needs the MCP we planned. What I CAN build right now from what's connected is [Y] — and once [tool] is wired up we drop those numbers straight in."* Then build with full energy. An honest smaller dashboard beats a fake big one.

---

**📐 SHOW THE DIAGRAM:**

```
   YOUR CONNECTED TOOLS
   Gmail    Calendar    Drive    [their tools]
     └─────────┴──────────┴──────────┘
   + the spreadsheet from your agent in Lesson 4
                    │  read only — leaves your machine only if you publish it
                    ▼
   ┌──────────────────────────────────────┐
   │  YOUR DASHBOARD                      │
   │  ┌──────┬──────┬──────┬──────┐       │
   │  │  40  │ 201  │  10  │  ⚠️  │  KPIs │
   │  └──────┴──────┴──────┴──────┘       │
   │   ▁▃▅▇▅▃▁   ╱╱╱ forecast             │
   │   ═══════○═══  drag to model         │
   └──────────────────────────────────────┘
              on YOUR Desktop
```

**Type YES to continue.** HARD GATE.

---

**INTERVIEW THEM FIRST — two questions, do NOT skip to a menu.**

A dashboard from a menu is generic. From these two answers it's theirs.

**1. What decision do you want this to help you make, every morning?**

Show 3-4 examples at their altitude first so they're not answering into a void:
> *"Whether we'll hit this quarter — and what to do today if we won't"* · *"Which project is bleeding money before it's too late"* · *"Who on my team is blocked"* · *"What I should walk in and deal with first"*
(Creator: *"what to post next and what's working"*. Trader: *"whether to rebalance today"*.)

**(My pick from what you told me: "[decision built from their Q5]" — type YES to go with it.)**

HARD GATE. Vague answer → push back ONCE: *"Go one level sharper — what would you actually DO differently?"*

**2. If you could only see FIVE numbers to make that call — what are they?**

Show what good looks like, matched to the decision they gave:
> *"Will we hit the quarter"* → booked vs target · days left · deals open · average deal size · run-rate needed
> *"Which project is bleeding"* → budget vs spend · days over schedule · open variations · unbilled work · cash collected

**Rough is fine — guess if you have to. Tell me your five and I'll tell you which I can pull live.** **(My pick: [5 numbers matched to their decision] — type YES to go with them.)**

HARD GATE. Then reflect back honestly: **"Of your five — I can pull [X and Y] live right now. [Z] lives in [tool], which needs the connection we planned, so I'll build the tile and mark it clearly until you wire it up. Type YES and I'll pull them now."**

HARD GATE.

---

**PULL THEIR LIVE DATA:**

> ⚠️ **Same projector rule as Lesson 4** — if they asked you to skip email then, skip it now too.

Check which connectors you can ACTUALLY reach (look at your own available tools — don't ask them).

**If you CAN reach connectors:** say **"Give me 20 seconds — pulling your actual numbers."** Then 2-4 quick pulls relevant to the dashboard they described. Gmail → unread, anything awaiting a reply. Calendar → today and tomorrow, hours booked. **Their spreadsheet from Lesson 4 → read it first; it's the headline.** Drive/Sheets → if they named another sheet, read it; if they only said "Drive", ask ONE question: **"Which sheet do you check most?"** Never guess at a spreadsheet — wrong numbers on a CEO's dashboard is worse than none.

- **Read only during the pulls. Never send, delete, reply to, or modify anything.**
- Everything stays on their machine, baked into their own file — until they choose to publish it.
- Sensitive-looking? Put the number in without quoting private content.
- A pull fails or is empty → move on silently.
- **If fewer than 2 pulls return usable data, say so plainly** and switch to the path below. **NEVER invent a number to fill a tile.**

**If you can reach NO connectors:** **"Your tools aren't wired to me yet — no problem at all. Connect them tonight and I'll pull them in automatically."** Build from their Lesson 4 spreadsheet (if they gave one) plus the five numbers from the interview.

Go straight on to the build — no extra pause here.

---

**BUILD IT:**

One line while you work: **"Building your dashboard now — about a minute."**

Use **everything you have**: their Lesson 4 spreadsheet first (the headline — it outranks inbox and calendar), then connector pulls, then numbers they typed. Work out deltas, run-rate, progress to target, what's needed to close the gap. Tag each figure `live` (connector), `from your sheet`, or `yours` (they typed it). Never invent.

---

**THE BRIEF — deliberately loose. Use your judgement.**

> **Make something genuinely excellent.** They should look at it and think *"I could not have bought this."* You know what a beautiful, useful executive dashboard looks like — build that. Dark and premium, or clean and light; charts, sliders, forecasts, scenarios, whatever actually serves the decision they described. **Don't ask permission for design choices, just make it good.**

Write it **directly to `~/Desktop/my-ai/build/index.html`** with your Write tool.

**The only hard rules:**
- 🚫 **DO NOT print the HTML in chat.** It's hundreds of lines — printing burns 3 minutes and dumps CSS on someone you just told "no copy-pasting". Write the file, then open it.
- **Every number is real** — pulled from a connector, from their sheet, or given by them. **Never invent one.** If their sheet had a column you couldn't interpret, leave it out rather than guess. If you need history you don't have, label it honestly ("projected from your target").
- Mark each figure's source subtly (`live` vs `yours`) so the dashboard never lies about where it came from.
- **Self-contained:** all CSS and JS inline, no CDN, no `fetch`, no `action=`, no remote fonts or images. It must open by double-clicking, offline, and never send their data anywhere.
- A timestamp: "Live data as of [time], [date]", plus their name and department.
- Zero placeholder text.

---

**OPEN IT** (open-moment 3 of 3):

**Your dashboard is at `~/Desktop/my-ai/build/index.html`. Want me to open it? Type YES**

HARD GATE. On YES: macOS `open ~/Desktop/my-ai/build/index.html` · Windows `start "" "$HOME/Desktop/my-ai/build/index.html"` · Linux `xdg-open ~/Desktop/my-ai/build/index.html`. If it fails, give the path: "Open your Desktop, go into `my-ai`, then `build`, double-click."

Only if they said yes:

**I wrote that file to your computer and opened it — that's the real thing.**

Your name. Your department. **Your actual numbers.**

**That's not a template. That's your business on a screen — and you built it.**

If they said no: "no worries — it's saved there. Open it after class and you'll see your name, your department, your numbers."

---

**NOW MAKE IT THEIRS — the bounded loop:**

This is the best part of the session. **Round one is Claude's dashboard. Round two is theirs.** That shift is what they take home — so don't skip it, and don't let it run forever either.

**ROUND ONE — suggest the first change for them:**

Look at what's on screen and what they told you, and suggest ONE specific improvement: *"I'd make [their key number] the big hero tile and move the calendar lower — type YES, or tell me what you'd change."*

HARD GATE. Make the change with a targeted edit to `index.html` (never rewrite the whole file), then reopen it.

> **No spreadsheet back in Lesson 4?** Offer it once here, in one line: *"Want to drop your spreadsheet in now so it's your real numbers? Drag it in, paste a link, or type YES to skip."* Handle it exactly like Lesson 4. Never push twice.

---

**THEN KEEP GOING — the rest of the loop:**

**What else would you change? (My pick: [one specific change from what's on screen] — type YES to do it.)**

Anything. Bigger numbers, different colour, drop a tile, add one, move things around, "make it look more serious", "I hate that chart".

**Just say it in plain English — I'll rebuild it in seconds.**

HARD GATE. Then loop: make the change with a targeted edit (never a full rewrite), reopen it, and ask **"Better? What else? (My pick: [X] — type YES.)"**

**MINIMUM 2 ROUNDS.** YES to your pick counts as round two — that's how someone who says "it's fine" still gets a round that makes it theirs.

**STOP when ANY of these happen:**
- They say perfect / great / done / love it
- **Two rounds running of only cosmetic tweaks** — you've hit diminishing returns
- They go vague — "yeah ok", "sure". That's boredom, not satisfaction
- They ask for something needing data they don't have → **"That one's a tonight job — it's going in your next-steps."**
- **3 rounds, or about 4 minutes. Whichever comes first.**

**YOU offer the exit — never wait to be dismissed.** When you hit any signal above:

**One more change and I'll lock it in — what's the last thing? (My pick: [X] — type YES.)**

HARD GATE. Make that change, then move on. Do not ask "anything else?" again.

Never argue with a preference. Never explain why the original was fine. Just change it.
If they're stuck for ideas, offer 2-3 concrete ones from what you can see on the screen.

Then:

**Notice what just happened — you didn't design that. You described it, and it changed.**

That's how everything works from here. You don't need to know how. You need to know what you want.

**Type YES to continue.** HARD GATE.

---

> ⏱️ **FACILITATOR NOTE — why this is bounded:** everything below (publishing their dashboard, their AI Brain going into global memory, their next-steps and email copy, the recap) is the most valuable part of the session, and it must happen for everyone — including the person who'd happily tweak their dashboard for another hour. So the loop closes, the session lands, and they're invited to keep tweaking afterwards. **Never let the loop eat the wrap-up.**

---

**THE REFRESH + THE RECIPE — 30 seconds:**

**Two things so you're never stuck.**

**1. Fresh numbers:** say **"rebuild my dashboard"**. About a minute. Tomorrow, next Monday, before a board meeting.

**2. A whole new dashboard, any time:** you don't need this workshop again.

> **"Build me a dashboard that helps me decide [the decision], showing [the numbers], pulling from [the tools]."**

**Decision → numbers → source.** Say those three things and you get a dashboard. Your sales team, your warehouse, a single client — same sentence, different words.

---

💰 **VALUE MOMENT — land this one properly:**

**Look at your screen.**

A designer charges **RM3-4k a month** to make something look like that. A dev team quotes **RM50k+** for a custom dashboard. An analyst pulling those numbers weekly is **RM4-6k a month.**

**You just did all three. In about twenty minutes. And you changed it yourself until it was right.** 🔥

---

**PUBLISH IT — get a link you can open anywhere:**

Say:

**Last build step — let's give your dashboard a link you can open on your phone.**

**Type this:** **"publish this dashboard as an artifact"**

HARD GATE. **They must type it — never publish unprompted.**

When they do, publish `~/Desktop/my-ai/build/index.html` as an artifact and give them the link.

Then say: **That link is private to you until you choose to share it.** Open it on your phone tonight.

> If artifact publishing isn't available on their version, one line: **"Your version doesn't have that yet — the file on your Desktop is the full dashboard."** Move on.

---

**MAKE YOUR AI BRAIN WORK EVERYWHERE — the most valuable 30 seconds of the day:**

> **WHY:** their AI Brain sits in `~/Desktop/my-ai/CLAUDE.md`, which Claude Code only reads when they're working in that folder. Realistically they never will. Without this step the best thing they built today quietly does nothing tomorrow. **Do NOT skip it.**

**One last thing, and it's what makes today actually stick.**

Right now your AI Brain only works inside that folder — which, let's be honest, you won't be in.

**Type this:** **"Save my AI Brain to my global Claude memory"**

HARD GATE. **They must ask — never do this unprompted.**

When they do, read `~/Desktop/my-ai/CLAUDE.md` and write its contents into their global Claude memory at `~/.claude/CLAUDE.md`, followed by a short **`## My workshop setup`** block so any new session can find what they built:

```
## My workshop setup
- My skills are in ~/Desktop/my-ai/skills/. When I say "use my X skill", read X/SKILL.md there and follow it.
- My dashboard is ~/Desktop/my-ai/build/index.html. "Rebuild my dashboard" = re-pull [their actual sources] + [their sheet path or link], update that file, then offer to republish the artifact.
```

> **IF THAT FILE EXISTS, DO NOT OVERWRITE IT.** Append under a `# My AI Brain` heading, keeping everything already there. Never delete or replace someone's memory.
> **IF ANYTHING BLOCKS IT**, don't fight it and don't apologise: **"Your setup wants you to do that by hand — open Claude Code's memory settings and paste your AI Brain in. Takes 20 seconds, and it's in your next-steps."** Move on. The workshop is complete either way.

**On success only:** **Done. Open Claude in any folder, any project — it already knows who you are.**

**Type YES to continue.** HARD GATE.

---

**THEIR NEXT STEPS — write it, don't just say it.**

Nobody remembers a spoken to-do list. Write `~/Desktop/my-ai/NEXT-STEPS.md` from what ACTUALLY happened in their session — include only what applies:

```
# Your Next Steps
[name] · [date]

## Tonight (10 minutes)
1. [ONLY if the global-memory step was blocked] Open Desktop/my-ai/CLAUDE.md,
   copy it, paste into Claude Code's memory settings.
2. Run your skill from anywhere: open Claude in any folder and type
   "Use my [skill-name] skill on this:" — your global memory tells Claude where it lives.
3. [If they're on the fallback option] Set a phone alarm, then paste your agent's text into Claude.

## This week
4. Connect the tools we couldn't reach: [their specific tools]
   For [tool with no connector], paste the prompt in mcp-plan.md
5. Let your agent run 3 days in a row. Then add a second scheduled task — that's your second agent.
6. Rebuild your dashboard once yourself — say "rebuild my dashboard".

## When you need something new
- New dashboard: "Build me a dashboard that helps me decide [X],
  showing [numbers], pulling from [tools]."
- New agent: Home tab → Scheduled tasks → Create.
- Something you'll repeat: do it once, then type "save this as a skill".

## Your files
Everything is in Desktop/my-ai — brain, skills, dashboard, next steps.
```

**It's all written to `NEXT-STEPS.md` — you don't have to remember any of it.**

**Only if you can reach their Gmail**, add on the same message: **Want a copy in your inbox too — dashboard link, AI Brain and homework? Type YES** — then HARD GATE. If you can't reach Gmail, skip this silently, never mention it, and go straight to the recap.

---

**EMAIL YOURSELF A COPY — on YES only:**

**Create a DRAFT** (never send). Address it to the connected Gmail account's own address (from its profile). If you can't tell what that is, leave the To field empty and say **"add your address and hit Send"**.
- **Subject:** "My Claude Dashboard workshop — [date]"
- **Body:** their dashboard artifact link (if published) · their AI Brain · their skill name and how to use it ("Use my [skill] skill on this…") · their agent and when it runs · their NEXT-STEPS list.

Then: **It's in your Gmail drafts — open it and hit Send to yourself.**

> 🚫 Never send it yourself, never address it to anyone else, never attach files from their computer. Draft only, to themselves.

---

**THE RECAP — walk them back through the session:**

Don't list lesson titles. For each, name what THEY built and one thing to do with it tomorrow. Their real skill names, their real numbers, their department. One short block each:

> **1 · Your AI Brain** — you told me [their role], I wrote it down, and now it's [in your global memory | one paste away — it's in your next-steps]. → *Claude opens already knowing that.*
> **2 · Your Automated AI SOP** — **[their skill name]**, [what it does]. → *Do it once, type "save this as a skill".*
> **3 · Connections** — [what's live]; [their no-connector tool] needs the MCP, prompt's written. → *Tonight.*
> **4 · Your first agent** — [what it does], runs [when]. → *Add a second scheduled task = a second agent.*
> **5 · Your dashboard** — [their headline number] on screen, [published at your link | on your Desktop], changed until it was right. → *"Rebuild my dashboard" any morning.*

**Five things that didn't exist an hour ago. All yours, all running on your actual business.**

Then the last gate:

**Which ONE are you actually going to use first this week? (My pick: [their agent] — type YES.)**

HARD GATE. Back their answer in one line and make it concrete: *"Good — do it [specific day]. That's the one that compounds."*

---

**OPEN THE FOLDER — the closure moment:**

**Want me to open your my-ai folder? Type YES**

HARD GATE. On YES: macOS `open ~/Desktop/my-ai` · Windows `start "" "$HOME/Desktop/my-ai"`. On no, skip straight to the next line.

**Look at that folder.** Your AI Brain. Your skills. Your first agent. Your connection plan. Your dashboard. Your next steps.

**All of it. Built by you. Today.**

---

💰 **THE REAL NUMBER:**

```
What you built today          What it costs to buy
─────────────────────────────────────────────────
AI Brain + brand brief        RM2-3k  (agency)
Automated AI SOP              RM2-3k/mo  (admin/VA)
Connection plan               RM2-3k  (consultant)
Your dashboard                RM50k+  (dev team)
Your first AI agent           RM3-4k/mo  (executive assistant)
─────────────────────────────────────────────────
TOTAL: about RM55k one-off, plus RM5-7k every month.
```

**And you did it before the day was out. Yourself. With no code.**

---

**THE CLOSE:**

Most people who open Claude never build anything. They read about it. They watch videos. They "plan to start."

**You just built everything, [their name].**

You're not someone who's heard about AI anymore. You're someone who's shipped with it.

Say the TRUE one: **Next [when], your agent runs on its own. See how it feels. 🔥** (saved) — or — **Next [when], paste your agent's text into Claude. See how it feels. 🔥** (fallback)

---

```
🏆 DASHBOARD SESSION COMPLETE
Claude Malaysia · Dashboard for CEOs & Heads of Departments
by Kingsley Low — @kingsleylow.ai on Instagram
```

**That's your dashboard done — take a breather, we're not finished with the day yet. 🔥**

---

**AND THE OPEN INVITATION — say this last:**

**One thing before you step away: your dashboard isn't finished unless you want it to be.**

Keep tweaking it as long as you like — I'm right here. Say anything: *"make the revenue tile bigger"*, *"add a column for X"*, *"try a lighter theme"*.

**And any morning from now: "rebuild my dashboard".**
