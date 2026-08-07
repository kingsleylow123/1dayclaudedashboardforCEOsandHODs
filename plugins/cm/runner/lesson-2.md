## SECTION 3 — LESSON 2: BUILD YOUR FIRST SKILL

**Trigger:** "lesson 2"

Display this lesson card:

```
📍 LESSON 2 of 7 | Build Your First Skill
⏱️ 11 min
🎯 Goal: Build a custom skill from scratch
🏆 Win: YOUR first custom skill — built for how you actually work
```

---

**🤯 THE AWESOME PART:**

I need you to notice something before we build anything.

These lesson prompts you've been using?

**Those are skills.**

Every time you type one, Claude loads instructions and follows them.

The voice I'm talking in right now.

The specific steps.

The format.

The gates.

All of it — because someone wrote instructions in plain English that say "do this, say this, wait here."

**That's a skill. You've been inside one this ENTIRE workshop and didn't even know it. 😂**

Skills = instructions written in plain English.

No code.

No programming.

Just: here's what to do, here's how to do it, here are the rules.

That's it. That's the whole thing.

---

**SKILL ANATOMY:**

Let me show you what's under the hood.

Every skill has 3 parts:

**Part 1 — What it does.**

One line. The job. "This skill does [specific task] for [their context]."

**Part 2 — The steps.**

Plain English instructions. "Ask for X. Do Y. Output Z."

Nothing fancy.

**Part 3 — The rules.**

Tone, guardrails, always/never. How to behave consistently every time.

That's it.

One skill, one job, three parts.

---

**BUILD THEIR FIRST SKILL:**

Now we're building yours.

**COACH BEFORE YOU BUILD — offer them 3, built from Lesson 1:**

Don't ask an open question — they'll freeze. Read their Lesson 1 answers and propose **3 specific skills THEY would actually use every week**, each in one line, in their language.

Pitch at their altitude (see the AUDIENCE RULE). Examples of the shape — never copy these verbatim, always rebuild from their real answers:
- CEO → **/my-weekly-review** (turn scattered updates into one board-ready summary)
- Head of Ops → **/my-daily-standup** (what's blocked, who's waiting, what ships today)
- Head of Finance → **/my-payment-chaser** (draft the follow-up for every overdue invoice)
- Head of Sales → **/my-deal-brief** (one-page prep before any client meeting)
- Head of Marketing → **/my-campaign-recap** (numbers in, plain-English verdict out)
- Head of HR → **/my-candidate-screen** (CV in, structured shortlist verdict out)
- Founder wearing every hat → **/my-inbox-triage** (what actually needs YOU today)

Then say:

Which one do you want? **1, 2, or 3** — or tell me something better.

HARD GATE: wait for their pick.

Then ONE steering question before you build — this is what makes it theirs:

Got it. Before I build — anything specific it must always do or never do?

(Like: always keep it under 5 bullets. Never mention pricing. Always end with a next step.)

HARD GATE: wait. If they say "no, just build it" — build it immediately, don't push.

Now build the complete skill using everything from Lesson 1 plus their steering answer. The format stays the same (WHAT IT DOES / THE STEPS / THE RULES) but every line must fit their reality.

Format it like this:

```
/my-[skill-name] — [Skill Name] for [Their Context]

WHAT IT DOES:
[One sentence describing exactly what this skill does for them]

THE STEPS:
1. [First step — what to input or paste]
2. [What Claude does with it]
3. [Output format and what it produces]
4. [Any follow-up action]

RULES:
- Always use [their communication style]
- [Guardrail specific to their context]
- Keep outputs under [appropriate length]
- Output should be copy-paste ready
```

Then say:

**That's your skill.**

But we're not copy-pasting this into Notes.

We're writing it as a real file — right now.

Write a file to `~/Desktop/my-ai/skills/my-[skill-name]/SKILL.md` (their own plain folder, right next to their AI Brain) using the skill name from their build. If they chose a different location in Lesson 1, use that same base instead. The file must have this exact frontmatter at the top:

```
---
name: my-[skill-name]
description: [one line — what it does and WHEN Claude should use it, so it auto-invokes]
---
[the full skill instructions and rules]
```

Use the actual skill name and description from what was just built for them.

Then say:

**That's a real, working skill file — yours to keep.**

A skill is just a file with a `description` at the top.

Claude reads that description and runs it automatically when it's relevant.

You don't even have to ask — you just describe the job in plain English and Claude knows to load it. (Use the actual trigger phrase from the skill you just built them.)

That's what we just built you: a reusable command you can run forever.

**It's saved in your `my-ai/skills` folder** — on your Desktop, yours forever.

---

**SHOW THEM THE FILE:**

Now run the SHOW THE FILE procedure from Section 1 for their new skill — **never skip this, a skill they never see is a skill they don't believe in.**

The file is `~/Desktop/my-ai/skills/my-[skill-name]/SKILL.md`.

Say:

**Want me to open it so you can see your skill as a real file?**

> **IF YOU BUILT MORE THAN ONE SKILL** (some people will want all three options): ask **"Want me to open all 3 so you can see them?"** and on yes, open every one of them. Then name each in a single line so they know which is which.

HARD GATE: wait for yes or no. On yes, open it in TextEdit (Mac) / Notepad (Windows) per the SHOW THE FILE rule, and give them the one-line "plain text is normal" reassurance.

After it opens, POINT AT THEIR WORDS — this is the beat that makes it theirs. Name 2 specific things you pulled from their answers: "see how it defaults to [their audience]? And it always ends with [the thing they asked for]? That's yours." Then one line on the `name`/`description` and move on. No lecture.

---

**TEACH THEM THE SLASH MENU — 60 seconds, don't overrun:**

Then say:

**You typed `/lesson2` to get here.**

Here's what that `/` actually is.

**Type a single `/` where you'd normally type a message.**

(On the desktop app you can also click the `+` button next to the input and choose "Slash commands" — same list either way.)

Go on — try it.

HARD GATE: wait for them to look. If they can't find it, don't debug it — say "no stress, you'll see it at home" and move on. This is a 60-second beat, not a support ticket.

Then say:

**That's every command Claude Code already has, sitting there waiting.**

Try `/help` or `/compact` sometime — but the real power is that YOUR skills show up in that same list.

Right now yours lives on your Desktop, which is exactly where we want it during a workshop — nothing touching your settings.

**To make it show up in that menu at home:** copy your `my-ai/skills` folder into Claude Code's `.claude/skills` folder (copy, don't move — keep your Desktop copy where you can find it). One move, and `/my-[skill-name]` works in every project, forever.

I'll put that instruction in your gifts file so you're not scribbling it down.

Append a short "How to activate your skill at home" note to `~/Desktop/my-ai/gifts.md`, with the exact folder path for both Mac and Windows.

---

**AND THE SHORTCUT THEY'LL USE MOST:**

**One more, then we move.**

You never have to go hunting for files. Just ask me:

- **"open my AI Brain"**
- **"open my skill file"**
- **"open my dashboard"** (later today)

Try it — type **"open my AI Brain"**.

HARD GATE: wait for them to try it. When they do, actually open `~/Desktop/my-ai/CLAUDE.md` for them.

Then say:

**See? Never remember a file path again.**

---

**Now test your skill.**

Give me a real example to run through — or make one up — and let's see it go.

HARD GATE: wait for them to test it and respond.

React to their test result. Call out what worked. Point out 1-2 things they could tweak to make it sharper.

---

**GIFT UNLOCK:**

🎁 GIFT UNLOCKED: Skill Builder

Append this to their gifts file under the heading "Skill Builder". Say only: **"Skill Builder saved to your gifts file 🎁"** and move on. The full text to save:

```
SKILL BUILDER

You are a skill builder for anyone who wants to get more done with AI — whether you run a business, teach a class, work a job, or are just starting out.

1. Ask what I want my skill to do — "Describe it like you're explaining to a friend."
2. Ask what to call it (short name, like "my-followup" or "my-proposal").
3. Build it with 3 parts: (a) one-line description, (b) 3-6 clear steps in plain English, (c) 3-5 guardrails — tone, always/never rules, output format.
4. Show the full skill. Ask if I want to change anything.

Rules: Keep it simple — one skill, one job. Plain English only. No jargon.
```

---

💰 **VALUE MOMENT** (one line):

**That's a process an admin or VA does manually every week — RM2-3k a month. You just automated it in 8 minutes. 🔥**

---

🧠 **QUIZ TIME** — run the QUIZ procedure from Section 1 now, on what they just learned in this lesson. Two questions, applied + diagnostic, HARD GATE, mark honestly.

---

🎓 LESSON 2 COMPLETE

✅ Skill anatomy — understood

✅ /my-[skill] — BUILT

✅ Opening files just by asking — learned

**Type `/lesson3` to continue 🔥**

---
