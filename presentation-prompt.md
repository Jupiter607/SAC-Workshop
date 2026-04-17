# Presentation Prompt

Copy and paste everything below into Google Gemini, ChatGPT, or any AI tool to generate your companion slide deck.

---

Create a polished, visually engaging Google Slides presentation (or PowerPoint) for a 2-hour hands-on faculty and administration workshop called **"Vibe Coding the Future of SAC"** at Santa Ana College.

This presentation is the **facilitator's companion** to an interactive participant website at **sac-workshop.vercel.app**. The slides guide the room through the workshop while participants follow along on the website on their phones or laptops. Every slide should tell the facilitator what to SAY, what to SHOW on screen, and what participants should DO on the website.

## Design Guidelines

- **Color scheme:** SAC Red (#C8102E), SAC Gold (#E5A823), dark charcoal background (#0b0e17), accent green (#00c896), purple (#7c6aff)
- **Typography feel:** Modern, bold, techy — think developer conference keynote, not corporate training
- **Layout:** Minimal text on slides. One big idea per slide. Use full-bleed color blocks, large type, and plenty of whitespace
- **Tone:** Energetic, empowering, no jargon without explanation. These are educators, not engineers
- **Include a QR code slide** early on that links to: **sac-workshop.vercel.app**

## Workshop Structure — Build These Slides in Order

### OPENING (Slides 1–6) — 5 minutes

1. **Title Slide:** "Vibe Coding the Future of SAC" — Santa Ana College, Spring 2026 — subtitle: "Build real tools with AI. No coding required."
2. **The Big Idea:** "What if you could build a custom tool for your department in 60 minutes — just by describing what you want in plain English?" — one sentence, large type
3. **QR Code Slide:** "Scan to open the workshop site" — show QR code for sac-workshop.vercel.app — instruct participants to open it now on their phone or laptop. Mention the contrast and text size buttons at the top right
4. **Agenda Overview:** Show the 4 phases with timing:
   - Phase 1 (0–15 min): The Vibe Shift — mindset + AI Studio tour
   - Phase 2 (15–45 min): AI Studio Sandbox — hands-on exploration
   - Phase 3 (45–105 min): Prototyping Lab — build your project
   - Phase 4 (105–120 min): Export & Deploy — make it real
5. **Ground Rules:** "There are no wrong prompts, only first drafts." — encourage experimentation, iteration, asking for help
6. **What You'll Walk Away With:** A working AI-powered tool you built yourself, saved as a reusable Prompt File, and optionally deployed via Google Apps Script

### PHASE 1: THE VIBE SHIFT (Slides 7–14) — 10 minutes

7. **"Stop Searching. Start Steering."** — The old way: Google a question, scroll through results, copy-paste. The new way: describe what you want, the AI builds it. You steer.
8. **What is Google AI Studio?** — A free, browser-based workspace from Google. No download needed. You chat with an AI model called Gemini, upload files, and export working code. Direct participants to the Resources section on the website.
9. **Live Demo: Open AI Studio** — Show aistudio.google.com on the projector. Walk through: the chat interface, the model selector (Gemini 1.5 Pro vs Flash), the paperclip icon for uploads, and the right sidebar settings.
10. **What Are System Instructions?** — "A paragraph you write before your first prompt that tells the AI who it is, who it's talking to, and how to behave. Think of it as the AI's job description." Show the formula from the website's Tips section:
    - You are a [role] at Santa Ana College.
    - Your audience is [who].
    - Always [behavior].
    - Never [thing to avoid].
    - Format output as [table / CSV / markdown / bullet list].
11. **What Is Temperature?** — Show the 3-range visual from the website:
    - 0.0–0.3: Focused & Factual (rubrics, data extraction, quizzes)
    - 0.4–0.6: Balanced (meeting summaries, rewrites, general Q&A)
    - 0.7–1.0: Creative & Varied (brainstorming, personas, lesson ideas)
    - Quick rule: "Need the same answer every time? Go low. Want to be surprised? Go high."
12. **Live Demo: System Instructions + Temperature** — Type a System Instruction live. Show the same prompt at Temperature 0.2 vs 0.9. Let participants see the difference in real time.
13. **"Natural Language Is the New Code"** — Inspirational moment. You don't need to learn Python. You don't need to learn JavaScript. You already speak the most powerful programming language — English (or Spanish, or Vietnamese, or any language).
14. **Transition:** "Now it's your turn. Open AI Studio and let's play."

### PHASE 2: AI STUDIO SANDBOX (Slides 15–20) — 30 minutes

15. **Sandbox Instructions:** "For the next 30 minutes, explore freely." Tell participants to:
    - Open AI Studio (link on the website's Resources section)
    - Try writing a System Instruction
    - Adjust Temperature and see what changes
    - Upload a PDF, image, or the sample video from the website
16. **Try This: Upload a PDF** — Walk through uploading a syllabus (participants can download the sample from Project 01 on the website or use their own). Ask Gemini to summarize it or create a student FAQ.
17. **Try This: Upload the Video** — Direct to Project 03 on the website. Download the sample lecture video. Upload it. Ask Gemini for timestamped notes and quiz questions.
18. **Try This: Turn on Google Search** — Show how to toggle the Google Search tool in the right sidebar. Ask a question that needs current data: "What are the 2026 transfer requirements for CSUF Business Admin?"
19. **The Checklist** — Direct participants to the Vibe Coding Checklist on the website. Walk through each of the 8 items together. Tell them to check each one off as they go.
20. **Transition:** "You've explored. Now let's build something real."

### PHASE 3: PROTOTYPING LAB (Slides 21–28) — 60 minutes

21. **"Choose Your Project"** — Direct participants to scroll to the Projects section on the website. Show the 7 project cards on the projector. Read the title and one-line description of each:
    1. Syllabus Sensei (Faculty) — PDF to FAQ + calendar CSV
    2. Equity Auditor (Faculty) — audit assignments for bias
    3. Lecture → Micro-Lesson (Faculty) — video to study guide
    4. Admin Workflow Automator (Admin) — meeting notes to action items
    5. Personalized Tutor (Faculty) — Socratic AI tutor
    6. SAC Transfer Tracker (Admin) — live transfer requirement search
    7. Confetti Blaster (Everyone) — fun AI code generation demo
22. **How to Pick:** Faculty → Projects 1, 2, 3, or 5. Admin → Projects 4 or 6. Want something fun and visual → Project 7. No wrong choice.
23. **Build Sprint Rules:**
    - You have 60 minutes
    - Follow the step-by-step instructions on the website (click "View build steps")
    - Use the sample data provided (copy or download buttons)
    - Iterate AT LEAST 3 times — the first output is a rough draft
    - If you get stuck, ask a neighbor or raise your hand
24. **Timer Slide:** Show a large 60:00 countdown (or just the number). Facilitator starts the timer.
25. **Halfway Check-in (30 min mark):** "Where are you? Have you iterated at least once? If your first output was perfect, you're not pushing hard enough. Ask the AI to make it better, shorter, more student-friendly, in a different format."
26. **10-Minute Warning:** "Start wrapping up. Make sure you can show your result to the person next to you."
27. **Pair & Share:** "Turn to your neighbor. Show them what you built. Tell them: what was your project, what worked, what surprised you?"
28. **Transition:** "Amazing work. Now let's make sure you don't lose it."

### PHASE 4: EXPORT & DEPLOY (Slides 29–34) — 15 minutes

29. **Save Your Work: Prompt Files** — Show how to click "Save" in AI Studio. Name your prompt clearly (e.g., "SAC Syllabus FAQ Generator"). This creates a reusable Prompt File you can open anytime.
30. **Get Code** — Show the "Get Code" button in AI Studio. Explain: this generates real code you can paste into Google Apps Script to make your tool live in Sheets, Docs, or Forms. You don't need to understand the code.
31. **Quick Demo: Apps Script** — If time allows, paste generated code into script.google.com and show it running in a Google Sheet. (Optional — don't rush this.)
32. **Share With Your Department** — Show how to share a Prompt File link. Encourage: "Send this to a colleague. They can duplicate it and customize it for their own courses."
33. **What's Next?** — Ideas for after the workshop:
    - Build another project from the website
    - Share your Prompt File at a department meeting
    - Try Gemini 1.5 Pro with your own course materials
    - Explore the website's Tips section for quick reference
34. **Closing Slide:** "You just built a real tool with AI in under 2 hours. Imagine what you'll build this semester." — Santa Ana College logo — website URL — your contact info

### BONUS SLIDES (Appendix)

35. **FAQ: "Is this replacing us?"** — No. This is a power tool, not a replacement. You're the expert. The AI is the assistant. You steer, it builds.
36. **FAQ: "Is this safe to use with student data?"** — Google AI Studio is a prototyping tool. Don't paste real student PII. Use synthetic/sample data for building. Deploy behind institutional auth for production use.
37. **FAQ: "What if the AI is wrong?"** — It will be, sometimes. That's why the checklist says "Verify AI output critically." Always fact-check before sharing with students.
38. **Resource Slide:** Repeat the QR code and website URL. List: AI Studio link, Apps Script link, ASSIST.org, SAC website.

## Speaker Notes

For EVERY slide, include detailed speaker notes with:
- Exactly what the facilitator should say (conversational tone, not scripted — bullet points)
- What to show on screen (website section, AI Studio demo, etc.)
- What participants should be doing at that moment
- Timing guidance (how long to spend on this slide)

## Output Format

Generate the complete slide deck as a structured outline with:
- **Slide number and title**
- **Visual description** (what the slide looks like — layout, colors, imagery)
- **On-screen text** (the actual words on the slide — keep it minimal)
- **Speaker notes** (detailed facilitator script)
- **Participant action** (what attendees should be doing)

Make it 34–38 slides total. Keep slide text punchy and large. All the detail goes in speaker notes.
