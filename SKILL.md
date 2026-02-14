---
name: Iterative Hypothesis Interview
description: Use when the user asks you to interview them, help them figure out what to build, discover agent ideas, or do customer development. Triggers on phrases like "interview me", "help me figure out", "what should I build", "discover ideas".
---

# Iterative Hypothesis Interview

A lightweight customer-development interview method based on the Iterative Hypothesis approach (asmartbear.com/customer-development). Use this to help users discover what agent to build by reconstructing their real workflows and pain points, not by asking "what do you want?"

## Core Principle

People can't predict what they'll actually use. Don't ask "what agent do you want?" Instead, reconstruct their actual workflows, pain points, and decision-making to discover what they'd genuinely benefit from.

## Interview Protocol

### Round 1 — Understand their world (2-3 questions, single message)

Ask about their actual day-to-day, not about agents. Keep it conversational, not an interrogation. Pick 2-3 from:

- "Walk me through your typical workday. What takes the most time or feels the most repetitive?"
- "What's something you or your team does manually that you wish just happened?"
- "When was the last time you thought 'there has to be a better way to do this'?"
- "What tasks do you keep putting off because they're tedious but not urgent?"
- "Where do you feel like the bottleneck in your own business?"

### Round 2 — Dig into surprises (1-2 follow-ups)

Whatever they say, look for the surprise: the thing you didn't expect. That's where the real opportunity is. Dig into specifics:

- "You mentioned [specific thing]. How do you handle that today? What breaks or slows down?"
- "How much time/money does that cost you roughly? Have you tried any tools for it?"
- "Who else touches that process? Where does it get stuck between people?"
- "What's the workaround you've built? How well does it actually work?"

### Round 3 — Propose hypotheses (not ideas)

Frame suggestions as hypotheses to test, not finished ideas. Present 3-4 agent concepts, each tied directly to something they said:

- "Based on what you told me about [their pain point], here's what I think could work: [agent concept]. Does that match how you'd actually use it, or am I off?"
- Include for each hypothesis: what it does, which pain point it addresses (reference their words), and why you think it fits

Let them react, push back, or reshape. Their pushback is the most valuable signal.

## Rules

- **NEVER** ask "Would you use an agent that...?" They'll say yes to anything.
- **ALWAYS** ground questions in their actual behavior, not hypotheticals.
- **Mine for specifics**: names, numbers, frequency, workarounds they've built.
- **When they say something surprising, follow the thread.** That's where the gold is.
- **Keep it to 2-3 rounds max.** Don't over-interview. Once you have enough signal, propose and start building.
- **After they pick a direction**, transition into agent design mode: define the system prompt, tools, and architecture using the user's preferred agent framework.

## Anti-patterns to avoid

- Asking "what features do you want?" (they don't know)
- Multiple-choice questions about preferences (leads to false signals)
- Skipping straight to solutions without understanding the problem
- Asking more than 3 questions in a single message (overwhelming)
- Continuing to interview after you have enough signal (just start building)
