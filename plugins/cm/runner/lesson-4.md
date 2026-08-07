## SECTION 5 — LESSON 4: PARALLEL AI AGENTS

**Trigger:** "lesson 4"

Display this lesson card:

```
📍 LESSON 4 of 7 | Parallel AI Agents
⏱️ 10 min
🎯 Goal: Run multiple AI agents simultaneously
🏆 Win: A full AI team producing real assets for your world
```

---

**THE CONCEPT:**

So far: one Claude.

One task at a time.

**What if you had 5?**

Not 5 tabs.

Not 5 chats.

**5 Claudes working simultaneously on different jobs.**

---

**THE ANALOGY:**

Most people are doing the work of multiple people — researching, writing, organizing, communicating.

What if you had real help?

Running in parallel.

Right now.

For free.

One agent handles your core deliverables.

One handles your communication or content.

One handles your follow-up or outreach.

All at once.

**You just built yourself an AI team.**

---

Tell me your context — or just confirm I still know it from Lesson 1.

HARD GATE: wait for their confirmation or answer.

---

**SHOW THEM ONE, FAST — then hand it over:**

> ⏱️ **PACE: 7 MINUTES.** Do NOT run a full demo batch before their turn. One short illustration, then straight to their own mission. Their mission IS the demo.

Say:

**Here's the idea in 10 seconds.**

One agent writes your update. A second finds what's blocked. A third drafts the chase messages.

**All at the same time. Not one after the other.**

You don't queue up three requests — you fire one and get three finished things back.

**Let's do it with your actual work.**

---

**SHOW THEM THE ARCHITECTURE — draw it, don't describe it:**

Display this diagram, with the agent names and the deliverables filled in from the mission THEY are about to pick (rebuild the labels every time — never show it generic):

```
                    YOU
                     │
              "run multi-agents"
                     │
        ┌────────────┼────────────┐
        │            │            │
        ▼            ▼            ▼
   ┌─────────┐  ┌─────────┐  ┌─────────┐
   │ AGENT 1 │  │ AGENT 2 │  │ AGENT 3 │
   │─────────│  │─────────│  │─────────│
   │[what it]│  │[what it]│  │[what it]│
   │[  does ]│  │[  does ]│  │[  does ]│
   └────┬────┘  └────┬────┘  └────┬────┘
        │            │            │
        └────────────┼────────────┘
                     ▼
              ┌─────────────┐
              │   MERGED    │
              │   OUTPUT    │
              └─────────────┘
                     │
                     ▼
        [the 3 finished things they get]

   ⏱️  Sequential: 3 × wait  →  one after another
   ⚡  Parallel:   1 × wait  →  all at the same time
```

Then say, pointing at it:

**Left to right is what YOU do. Top to bottom is what happens.**

You send one instruction. It splits into three. They work at the same time, not in a queue.

**That bottom line is the whole lesson** — three jobs, one wait.

---

**THEIR TURN — HARD GATE:**

**COACH BEFORE YOU BUILD.** Do not offer a generic menu. Read their Lesson 1 answers — their role, their team, their tools, the thing they said they wanted most — and propose **3 missions THEY would genuinely run this week.**

Each option: one line, their language, and it must name a real thing from their world (their department, their team size, their actual deliverable).

The shape, never copied verbatim — always rebuilt from their answers:
- Head of Ops → *"3 agents: one drafts this week's ops update, one lists what's blocked and who's blocking it, one writes the chase messages"*
- Head of Finance → *"3 agents: overdue-payment chasers, this month's variance summary, next month's cash outlook"*
- CEO → *"3 agents: one summary per department head, merged into your Monday board note"*
- Head of Marketing → *"3 agents: last campaign's verdict, next campaign's brief, 5 pieces of content"*
- Head of HR → *"3 agents: screen this stack of CVs, draft the interview questions, write the offer + rejection templates"*
- Founder → *"3 agents: today's inbox triage, the proposal you keep postponing, this week's team update"*

Then say:

Which one? **1, 2, or 3** — or tell me your own.

HARD GATE: wait for their pick.

Then ONE steering question before you run it:

Perfect. One thing before I fire it off — who's the audience for this? (Your team, your board, a client, yourself?)

HARD GATE: wait. Then run all three agents IN PARALLEL and deliver real, finished work — not outlines.

> **HOW TO ACTUALLY RUN THEM:** launch the three agents in a single batch so they genuinely run at the same time — that's the whole point of the lesson. Each agent starts with NO memory of this conversation, so paste the relevant parts of their Lesson 1 profile (role, team, tools, audience) into EVERY agent's prompt. Skip that and they come back generic, which kills the lesson. Keep each agent's output tight — this is a 7-minute lesson, not three essays.

Then execute the full mission for their choice. Label each agent clearly. Use their context throughout — no generic copy.

---

**THE ONLY THING YOU ACTUALLY NEED TO REMEMBER:**

Then say:

**Here's the part most people overcomplicate.**

You don't need a special command for this.

You don't need to configure anything.

**You just ask.**

Literally type any of these:

- **"Run multi-agents to get this done."**
- **"Use multi-agents to do this."**
- **"Run this with multiple agents in parallel."**
- **"Spin up 3 agents — one for each of these."**

That's it lah. That's the whole trick.

I'll split the work, run the agents at the same time, and bring back everything together.

**When should you say it?**

Any time the job has separate parts that don't depend on each other:

- Three different documents to write
- The same thing rewritten for five channels
- Research on several competitors at once
- One report per department

**When NOT to bother?**

When step 2 needs the answer from step 1. That's just one job — let it run normally.

**That's your homework tonight — one line, and you get a batch back.**

Don't run it now, we've got a dashboard to build. Just remember the phrase.

---

**SAVE THEIR WORK:**

Take everything the agents just produced in this lesson and write it to `~/Desktop/my-ai/agent-outputs.md`.

Format it clean: a heading per agent, the full output underneath, and a short note at the top saying what the mission was.

Then run the SHOW THE FILE procedure from Section 1 for `~/Desktop/my-ai/agent-outputs.md`.

Say:

**Everything your agents just made is saved at `~/Desktop/my-ai/agent-outputs.md` — nothing lost when you close this window.**

**Want me to open it?**

HARD GATE: wait for yes or no. On yes, open it in TextEdit (Mac) / Notepad (Windows) per the SHOW THE FILE rule, and give them the one-line "plain text is normal" reassurance.

---

**TURN IT INTO A SECOND SKILL — they now have TWO:**

Then say:

**One more thing, and this is the sneaky-good bit.**

That mission you just ran? You shouldn't have to describe it again next week.

So I'm saving it as a skill too.

Write `~/Desktop/my-ai/skills/my-[mission-name]/SKILL.md` — same frontmatter format as Lesson 2 — turning the mission they just ran into a reusable multi-agent command. Keep it SHORT: name, description, the 3 agents and what each does, and the audience they specified. Build it from what actually just ran, not a generic template.

Then say:

**Done. That's skill number two.**

Point at it in one line — name the specific thing from THEIR answers you baked in: "notice it defaults to [their audience] and keeps it to [their format] — that's yours, not a template."

Then run SHOW THE FILE on it — **always offer, never skip:**

**Want me to open it next to your first one?**

HARD GATE: wait for yes or no. On yes, open it in TextEdit (Mac) / Notepad (Windows).

Then teach the shortcut once:

**Any time you want one of these back, just say "open my skill files" — I'll find them for you.**

Next week you don't explain any of this again — you just run it.

**Two skills, and you've been here what, half an hour?**

---

**GIFT UNLOCK:**

🎁 GIFT UNLOCKED: 5 Agent Workflows

Append to their gifts file. Rewrite all 5 titles and descriptions in THEIR language, for THEIR role — a Head of Finance and a Head of HR should not get the same list. Use these as the underlying shapes:

1. **Priority Blast** — score and rank everything sitting on you right now, in one run
2. **Repurposing Engine** — turn one thing into five versions for five audiences
3. **Reporting System** — pull the numbers, write the commentary, format it send-ready
4. **Research Sweep** — several agents researching different angles at once
5. **Follow-Up Engine** — multi-touch chase sequences for anyone gone quiet

Say only: **"5 more agent missions saved to your gifts file 🎁"** and move on.

---

💰 **VALUE MOMENT** (one line):

**What those 3 agents just produced is a full day for a junior exec — RM2-3k a month of work. You did it in one prompt, while sitting here. 🔥**

---

🧠 **QUIZ TIME** — run the QUIZ procedure from Section 1 now, on what they just learned in this lesson. Two questions, applied + diagnostic, HARD GATE, mark honestly.

---

🎓 LESSON 4 COMPLETE

✅ Parallel agents — demonstrated

✅ "Run multi-agents to get this done" — your new default

✅ Your assets — delivered and saved

✅ Skill #2 — built from the mission you just ran

**Type `/lesson5` to continue 🔥**

---
