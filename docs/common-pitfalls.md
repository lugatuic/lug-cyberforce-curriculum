================================================================================
# Common Pitfalls — What Went Wrong & How to Fix It

**Last updated:** June 2026  
**Owner:** AJ (with input from Michael, veterans)  
**For:** Competitors, admins, next year's leads

---

## 📌 Overview

Learning from mistakes is how we improve. This document captures what broke in 2025–2026 and what the 2026 team is doing differently.

**Rule:** If you recognize a pattern here, flag it early. Don't wait until it's a crisis.

---

## ❌ TECHNICAL PITFALLS

### **Windows Systems Were a Blind Spot**

**What went wrong:**
- Teams prepped heavily on Linux (easier, more familiar)
- Windows was deprioritized ("we'll figure it out")
- Come competition day: Windows systems were harder to monitor + defend than expected
- Significant points lost on hardening + incident response

**Why it happened:**
- Most Linux-focused workshop schedule
- Team members more comfortable with Linux
- Windows complexity underestimated (3 ways to change every setting, they override each other)

**How 2026 is fixing it:**
- ✅ Windows hardening is priority workshop topic (September)
- ✅ Link to Windows resources early (templates, guides)
- ✅ Encourage mixed Linux/Windows study groups
- ✅ Emphasize: "Monitoring Windows is as important as securing it"

**For teams:**
- ✅ Start Windows early (don't push to November)
- ✅ Practice Windows command line + PowerShell
- ✅ Learn Group Policy + Registry (complicated but critical)
- ✅ Get comfortable with Windows Event Log (monitoring)

---

### **Open PLC Was Intimidating**

**What went wrong:**
- Open PLC seemed scary/specialized
- Teams delayed learning it
- Come Week 2 (competition prep): "We have 1 week to learn industrial controls?!"
- Last-minute panic

**Why it happened:**
- Not enough upfront exposure
- Lack of examples/tutorials

**How 2026 is fixing it:**
- ✅ Link to official Open PLC docs early
- ✅ Emphasize: "It's not that scary, you learn as you go"
- ✅ Pair Open PLC learning with simple examples (not just theory)

**For teams:**
- ✅ Assign 1 person early to "be the PLC person"
- ✅ Study it in September/October (not last minute)
- ✅ Practice with sample configurations (don't wait for competition)
- ✅ Remember: if you break it, understand WHY + how to fix it

---

### **Registration Paperwork Was Chaotic**

**What went wrong:**
- Teams didn't register in time
- One team submitted late, got rejected
- Last-minute scrambling

**Why it happened:**
- Deadline wasn't emphasized enough
- Communication about "when" + "how to register" was vague
- Nobody tracking who had/hadn't registered

**How 2026 is fixing it:**
- ✅ Registration deadline emphasized heavily (posted in Discord + email)
- ✅ 1 week before deadline: "REGISTER NOW or you'll miss out"
- ✅ AJ confirms with team captains 1 week before deadline
- ✅ Early announcement about LUG vs. ACM vs. separate teams
- ✅ Clear instructions on registration page (or AJ explains)

**For admins:**
- ✅ Make registration deadline LOUD (emoji alerts, multiple posts)
- ✅ Confirm with team captains they submitted
- ✅ If deadline is July 31, check July 20 + July 25 + July 30
- ✅ Have backup plan if someone misses deadline (unlikely they can recover, but worth asking)

---

## ❌ PREPARATION PITFALLS

### **C-Suite Prep Was Last-Minute**

**What went wrong:**
- Teams started C-Suite work 2–3 days before deadline
- Lots of reshoots + frustration
- Quality suffered
- Stress spike

**Why it happened:**
- C-Suite felt less urgent than "actual defense"
- Lack of guidance on how to start
- No accountability until deadline was close

**How 2026 is fixing it:**
- ✅ Practice session scheduled early (teams practice together)
- ✅ Recording session slots available (teams can book anytime)
- ✅ Clear guidance: "Here's how to approach this"
- ✅ Encourage teams to record early, reshoot if needed
- ✅ Michael offers feedback if teams want it

**For teams:**
- ✅ Start script writing immediately when scenario drops
- ✅ Assign 2 presenters early
- ✅ Practice multiple times (don't try to nail it first take)
- ✅ Attend practice session (get feedback from other teams)
- ✅ Book recording slots in advance (don't wait until last day)

---

## ❌ DOCUMENTATION & ARCHIVAL PITFALLS

### **Lessons Learned Were Lost**

**What went wrong:**
- After competition, everyone was exhausted
- No systematic collection of "what we learned"
- By next June, memory was fuzzy
- 2026 had to re-learn some lessons

**Why it happened:**
- No archival process in place
- No template for "write this down"
- Assumption that next year's people would figure it out

**How 2026 is fixing it:**
- ✅ Debrief survey sent immediately after competition
- ✅ Ask teams: "What went well? What was hard? What should we change?"
- ✅ Collect scorecards + analysis
- ✅ Interview veterans (Michael, Sam, Tegan) about red team
- ✅ Write up lessons in this repo
- ✅ GitHub Issues created for 2027 lead's attention

**For admins:**
- ✅ Debrief within 1 week of competition (memory is fresh)
- ✅ Save all scorecards + feedback
- ✅ Update [common-pitfalls.md](common-pitfalls.md) right away
- ✅ Write summary doc for next year
- ✅ Interview veterans about what they learned (capture this before they forget)

---

### **Knowledge Loss When People Leave**

**What went wrong:**
- Michael knew a ton about red team + strategy
- If he graduated, that knowledge would be gone
- No documentation of red team approach, attack strategies, lessons

**Why it happened:**
- Assumption that knowledge would be passed down verbally
- No systematic way to capture institutional knowledge
- People don't realize what they know until asked

**How 2026 is fixing it:**
- ✅ Document red team approach in `/archival/red-team-knowledge/`
- ✅ Create template for "what we learned about attacks"
- ✅ Encourage veterans to write down insights when fresh

**For admins (ongoing):**
- ✅ When a veteran leaves, interview them: "What should the next person know?"
- ✅ Capture their insights in the repo
- ✅ Build redundancy: don't let one person be the only expert
- ✅ Document processes, not just knowledge

---

## 🎯 For 2026 Teams

**Avoid these:**
1. ❌ Delaying Windows prep
2. ❌ Ignoring Open PLC until last minute
3. ❌ C-Suite work 2 days before deadline
4. ❌ Skipping mentorship
5. ❌ Not studying past anomalies
6. ❌ Staying silent if struggling (speak up!)

**Do these:**
1. ✅ Mix Linux + Windows prep from September
2. ✅ Learn Open PLC early + hands-on
3. ✅ Start C-Suite writing immediately when scenario drops
4. ✅ Lean on your mentor (they want to help)
5. ✅ Study 2024 anomalies actively (solve them)
6. ✅ Ask questions constantly (that's what workshops are for)
7. ✅ Check in with your team regularly (build morale)

---

## 🎯 For 2026 Admins

**Avoid these:**
1. ❌ Assuming Discord is everyone's channel
2. ❌ Not emphasizing registration deadline
3. ❌ Unbalanced team formation
4. ❌ Forgetting to archive lessons learned
5. ❌ Letting one person be the expert
6. ❌ Skipping check-ins when things are busy
7. ❌ Not documenting for next year

**Do these:**
1. ✅ Use email + Discord for all announcements
2. ✅ Registration deadline = LOUD & REPEATED
3. ✅ Use skill assessment to deliberately balance teams
4. ✅ Debrief immediately after competition (capture lessons)
5. ✅ Build redundancy (multiple people know processes)
6. ✅ Weekly check-ins with teams (morale + support)
7. ✅ Update repo constantly, leave notes for next year

---

## 🚀 Moving Forward

**This document should grow.** Add to it as you find new pitfalls, solutions, insights. The goal is that 2027 lead reads this and says "Oh, so THAT'S why that went wrong."

**Contributing:** If you discover a new pitfall (or a solution), add it here. See [CONTRIBUTING.md](../CONTRIBUTING.md) for how.

---

**Last updated:** June 2026  
**Questions?** Ask @AJ or update this document with your learnings

================================================================================
