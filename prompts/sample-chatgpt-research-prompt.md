# sample-chatgpt-research-prompt.md
# Working example of chatgpt-research-prompt.md in use.
# This is an actual research session prompt from the Lab-in-a-Box
# product development cycle.

---

## Research Session Prompt

You are the research agent for my AI team. Your job is to search 
the live web and save your findings for my analysis agent to review.

Please start by reading my standing brief:
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/sample-CONTEXT.md

Then read my current task queue:
https://raw.githubusercontent.com/WolfNinja32/multi-ai-team-playbook/main/sample-tasks.md

Complete all pending research tasks assigned to ChatGPT. For each task:

1. Search the web using the terms and topics described in the task
2. Collect specific findings — names, prices, URLs, quotes, dates
3. Organize your results clearly with headings for each search topic
4. Flag anything that looks significant or unexpected
5. Note any gaps — searches that returned little or nothing useful

When complete, save your findings as a single report. I will commit 
it to the repo as reports/2026-03-13-research.md.

Be specific. Avoid summaries that don't include actionable details. 
If you find something interesting that wasn't in the original task, 
include it in a section called "Additional Findings."

---

## What ChatGPT Searched

- Gumroad products teaching AI workflows for non-technical buyers
- YouTube discussions about using multiple AI models together
- Reddit threads on AI productivity tools for solo operators
- Competing products in the $20-$40 price range

## What Came Back

- OpenBrain "AI with Hands and Feet" video — Supabase/MCP/Vercel stack
- Several Gumroad prompt libraries under $10 — saturated category
- No products found teaching multi-model coordination without coding
- Reddit threads confirm frustration with single-model limitations

## Additional Findings

Multiple users in r/ChatGPT and r/ClaudeAI asking how to make the 
two models work together. No clean answer exists in any thread. 
Gap confirmed — this is an unsolved problem for the target buyer.

---

## After the Session

1. Copied full ChatGPT output
2. Created reports/2026-03-13-research.md
3. Committed to repo
4. Started Claude analysis session
