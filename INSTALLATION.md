# Installation

This repo is a plug-and-play agentic workflow for marketing execution.

It works with any AI tool that can load markdown “skills” (Codex, Claude, ChatGPT custom GPTs, internal agent runners, etc.).

## 1) Copy into your project

Copy the `agents/` folder into your workspace.

You now have:

- Core control agents (`agents/core`)
- Motion engines (`agents/motions`)
- A context layer you customize (`agents/core/context-layer.md`)

## 2) Customize your context (required)

Open:

`agents/core/context-layer.md`

Fill in:

- Category & Position
- Core Differentiation
- Revenue Motions
- Target Segments
- Proof & Authority

Keep it short. Make it real.

## 3) How to use (recommended default)

Start requests with:

“Act as orchestrator.”

Then paste your ask.

Example:

Objective: Improve enterprise landing page conversion  
Motion: Enterprise  
Funnel stage: Consideration  
Asset(s): Landing page rewrite + hero section variants  
Metric: Demo requests

If you don’t know the motion, just say so — orchestrator + motion-router will infer it.

## 4) Using with auto-select (Codex-style)

If your environment auto-selects skills:

- Keep `orchestrator` as your starting point.
- When you ask for an asset directly (e.g. “write a landing page”), the orchestrator should still generate a brief and route to the right motion.

If you notice the AI skipping structure:
- Start your message with “Act as orchestrator.”
- Or paste the “Quick Start Prompt” below.

## Quick Start Prompt (copy/paste)

Act as `orchestrator`.  
Use `context-layer` as the source of truth.  
Create a brief, route via `motion-router`, then propose next steps.  
If this is high-stakes, require `quality-gate` before final.

Here is my request:
[Paste request]

## 5) Extending the system

Common extensions:

- Add execution agents in `agents/execution/` (copy, social, seo, cro, paid)
- Add more motions (e.g. “community”, “events”, “pricing”)
- Add SOP templates under `agents/sop/`

Keep the core logic simple:
Context → Motion → Execution → Quality gate.
