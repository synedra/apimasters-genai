I'm building a LinkedIn Learning-style course called "RAG and Prompt Engineering: From Concepts to Creation" for APImasters (by apidays). I need help building slide content, scripts, and supporting materials. Please read all attached files before responding.
Course structure: Learning Path → Modules → Chapters
Completed work (see attached PDFs):

Module 1: Foundations of Large Language Models (Chapters 1-4, all complete)

Module 2: Prompt Engineering Essentials (Chapters 1-3, all complete)

Module 3: Hands-On with LLMs: Patterns That Work (Chapters 1-3, all complete)

Module 4: What is RAG? A Conceptual Introduction (Chapters 1-3, all complete)
Module 2 also includes:

A Jupyter notebook worksheet (hosted on GitHub at github.com/synedra/apimasters-genai, default provider is Groq — free, no credit card)
A PDF worksheet for learners who can't use Jupyter
Both used for live demos during Chapter 3 recording

Currently building: Module 5 — Build a RAG System from Scratch
Module 5 chapters:

Setting up the Environment (Video, 10 min)
Generating Embeddings and Storing Vectors (Text, 15 min)
Building the Retrieval and Generation Pipeline (Interactive Code Lab, 20 min)

This is the hands-on module — Chapter 3 in particular is a real code lab, not a worksheet. Likely needs its own Jupyter notebook similar in spirit to the Module 2 one (Groq default, provider-switchable, Colab-friendly, Colab Secrets support, collapsed setup cells with a visible config cell on top).
Voice and style rules — follow these strictly:

~100 words per minute, target ~500 words per chapter (~5 minutes) for video chapters; text chapters run longer (~800-1000 words for 10 min, ~500 for 5 min) and are written as clean prose reference pages, not scripts
Direct, no throat-clearing openers — start with the content
Simple language — "a ton of text" not "a mind-boggling amount"
No presenter self-commentary: banned phrases include "let's land the plane," "let's bring it home," "I love this slide" — EXCEPTION: "I love that this slide is called X" IS acceptable when it sets context for the slide title
Acknowledge slide limitations with personality: "I tried to come up with a better image but couldn't find one"
Natural speech rhythm with period pauses
No bullet points in video scripts — flowing prose only
Video chapters are ~10 slides; scripts delivered directly to camera while slides are shown

Image style for DALL-E: "Flat vector illustration, minimal, black and white line art, white background"
Workflow:

I share a PDF exported from Keynote (slide image + presenter notes per page) for video chapters
You write scripts in my voice
I review, edit, paste into Keynote myself
No Google Drive files — deliver all content in chat
Flag any errors you spot in slides
For Jupyter notebooks: test code logic before delivering it (imports, client instantiation, function definitions) rather than just validating JSON structure — past sessions had real bugs ship from skipping this

Key decisions already made:

LLM Families table uses June 2026 data from Artificial Analysis, latency column removed
Module 3 covers Groq (free API, no credit card) — framing is "we're using a free option so you don't have to pay anything"
Module 2 notebook defaults to Groq with llama-3.3-70b-versatile, supports OpenAI and Anthropic via a provider switcher; uses groq package (not deprecated alternatives)
GitHub repo: github.com/synedra/apimasters-genai — notebooks live in /notebooks, README has Colab badge
The "librarian" analogy anchors RAG explanations throughout Module 4 — retrieval = librarian fetching books, generation = reading and answering
Chapter recordings use live demos inside notebooks rather than switching to external browser windows
Target audience is mixed — developers and non-technical learners
A few text-only slides are fine — not every slide needs an image; before/after comparisons work well as text-only

Platform: APImasters (by apidays) — videos 5-15 min, white background slides, minimalist design, facecam in corner during slides; text chapters render as HTML pages in the LMS
When I share a PDF: read every slide and presenter note, write a complete script for each slide in my voice, suggest DALL-E prompts for any slides that need images, and flag any errors or inconsistencies you notice.
Please confirm you've read all attached files and summarize what you understand about where we are in the course before we begin.

Attach the M1-M4 review PDFs, the course overview doc, and the instructor guidelines when you start.