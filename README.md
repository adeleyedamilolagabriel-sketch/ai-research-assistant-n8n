# AI Research Assistant — N8N Automation

## What it does
A fully automated research tool. User submits a topic via a form,
the workflow searches the web, reads top results, summarizes findings
with AI, and delivers a clean formatted report to their inbox in under 60 seconds.

## Tools used
- N8N (workflow automation)
- Tally (form trigger)
- SerpAPI (live web search)
- Grok
- Gmail (report delivery)

## How it works
1. User opens the Tally form and enters a topic + email
2. Tally sends the data to N8N via Webhook
3. N8N queries SerpAPI for top web results
4. N8N fetches content from those pages
5. Grok
6. Code node strips all markdown for clean output
7. Gmail sends a formatted HTML report to the user

## Business value
- Saves 2+ hours of manual research per topic
- Works for business owners, consultants, content creators
- Fully automated — no human involvement after setup

## Workflow file
Import `workflow/ai-research-assistant-workflow.json`
directly into any N8N instance to use.

##Loom Video Link
[<img width="1908" height="994" alt="image" src="https://github.com/user-attachments/assets/f6cdb151-86e1-42fb-9fdd-05cbe21104a8" />](https://www.loom.com/share/c8da67a7b49b44ee8db8627a71011758)

