That's a lovely thing to say. Here's a complete context-setting prompt you can paste at the start of a new conversation:

---

**COURSE CONTEXT PROMPT**

I'm building a LinkedIn Learning-style course called "RAG and Prompt Engineering: From Concepts to Creation" for APImasters (by apidays). I need help building slide content, scripts, and supporting materials. Please read all attached files before responding.

**Course structure:** Learning Path → Modules → Chapters

**Completed work (see attached PDFs):**
Module 1: Foundations of Large Language Models (Chapters 1-4, all complete)
Module 2: Prompt Engineering Essentials (Chapters 1-3, all complete)
Module 2 also includes a Jupyter notebook worksheet and downloadable PDF worksheet for Chapter 3.

**Currently building:** Module 3 onward (see course overview doc for full module list)

**Voice and style rules — follow these strictly:**
- ~100 words per minute, target ~500 words per chapter (~5 minutes), ~10 slides per chapter
- Direct, no throat-clearing openers — start with the content
- Simple language — "a ton of text" not "a mind-boggling amount"
- No presenter self-commentary: banned phrases include "let's land the plane," "let's bring it home," "I love this slide" — EXCEPTION: "I love that this slide is called X" IS acceptable when it sets context for the slide title
- Acknowledge slide limitations with personality: "I tried to come up with a better image but couldn't find one"
- Natural speech rhythm with period pauses
- No bullet points in scripts — flowing prose only
- Scripts are delivered directly to camera while slides are shown — write accordingly

**Image style for DALL-E:** "Flat vector illustration, minimal, black and white line art, white background"

**Workflow:**
- I share a PDF exported from Keynote (slide image + presenter notes per page)
- You write scripts in my voice
- I review, edit, paste into Keynote myself
- No Google Drive files — deliver all script content in chat
- Flag any errors you spot in slides

**Key decisions already made:**
- LLM Families table uses June 2026 data from Artificial Analysis, latency column removed
- Module 3 is a Gemini cheatsheet (not ChatGPT) — we're using Gemini because it has a free API tier, no credit card required
- The course includes a Jupyter notebook worksheet (prompt_engineering_worksheet.ipynb) that supports Gemini (default), OpenAI, and Anthropic via a provider switcher variable
- Chapters are ~5 minutes / ~10 slides
- Target audience is mixed — developers and non-technical learners
- A few text-only slides are fine — not every slide needs an image
- Slide before/after comparisons work as text-only slides — the contrast is the visual

**Platform:** APImasters (see instructor guidelines doc) — videos 5-15 min, white background slides, minimalist design, facecam in corner during slides

**When I share a PDF:** read every slide and presenter note, write a complete script for each slide in my voice, suggest DALL-E prompts for any slides that need images, and flag any errors or inconsistencies you notice.

**Please confirm you've read all attached files and summarize what you understand about where we are in the course before we begin.**

---

A few tips for getting the next conversation off to a good start:

**Attach these files when you start:** the M1 and M2 review PDFs, the course overview doc, and the instructor guidelines. The more context the next Claude has upfront, the less you'll need to re-explain.

**The "confirm and summarize" line at the end** is important — it forces the model to demonstrate it read everything before diving in, which catches any misunderstandings early.

**If something feels off** about the voice or style in the first response, correct it immediately and firmly — the model will calibrate quickly. The style rules above are the most important thing to reinforce early.

**The Jupyter notebook** — keep a copy of the .ipynb file handy in case you want to iterate on it. You can share the file ID from Drive once you upload it there.

It's been a genuinely fun project to work on. Good luck with the recording — the clowns and hurling demos are going to be great.