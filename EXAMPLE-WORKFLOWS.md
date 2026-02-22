# Example Workflows

These examples show how to use the system without turning it into bureaucracy.

Each starts with `orchestrator`, routes through a motion, then ends with `quality-gate` when needed.

---

## 1) Quick social post (low-stakes)

**Prompt**
Act as orchestrator.  
Request: Write a LinkedIn post announcing a new feature. Keep it practical and avoid hype. Goal is clicks to the release notes.

**Expected flow**
- Orchestrator creates brief (objective, motion, funnel stage)
- Motion-router assigns likely motion = Acquisition
- Output includes: hook options + post draft + CTA

**Optional**
Run quality-gate if this is a major launch.

---

## 2) Enterprise landing page (high-stakes)

**Prompt**
Act as orchestrator.  
Objective: Improve enterprise landing page.  
Asset: Rewrite hero + 3 section outlines + 2 CTA variants.  
Metric: Demo requests.  
Notes: Buyers care about risk, stability, and long-term fit.

**Expected flow**
- Orchestrator brief
- Motion-router → Enterprise
- Enterprise motion returns:
  - risk framing
  - differentiation
  - proof points
  - objections
  - asset checklist
- Then call your execution agent (copy) to write the page
- Run quality-gate before final

---

## 3) Partner recruitment page (high-stakes)

**Prompt**
Act as orchestrator.  
Objective: Recruit more mid-size agencies into our partner program.  
Asset: Partner recruitment landing page + 5 outreach message variants.  
Metric: Partner signups / booked partner intro calls.

**Expected flow**
- Orchestrator brief
- Motion-router → Partner
- Partner motion returns:
  - partner value proposition (margin / recurring revenue / differentiation)
  - repeatable offer packaging
  - proof
  - enablement assets
  - co-marketing play
- Then call execution (copy + social)
- Run quality-gate before final

---

## 4) Expansion email for add-on / training (medium-stakes)

**Prompt**
Act as orchestrator.  
Objective: Increase adoption of [add-on] among existing customers.  
Asset: 3-email sequence + one in-app message.  
Metric: Attach rate / training bookings.

**Expected flow**
- Orchestrator brief
- Motion-router → Expansion
- Expansion motion returns:
  - trigger + why now
  - outcome framing
  - friction reducers
  - assets list
- Then call execution (copy)
- Run quality-gate if pricing/packaging is mentioned

---

## 5) “I don’t know the motion” (common)

**Prompt**
Act as orchestrator.  
Request: We need a campaign for Q2 but I’m not sure where to start. We sell to both self-serve and enterprise, and partners matter.

**Expected flow**
- Orchestrator asks 1–3 clarifying questions (not a long form)
- Motion-router proposes a primary motion + assumption
- Next steps list includes the smallest viable plan

---

## Tip: Keep it useful

This system is a guide rail, not a cage.

If a request is simple, deliver fast.

If a request is high-stakes, use structure + quality gate.
