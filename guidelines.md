# CV Guidelines

General best practices for writing a strong tech / engineering CV. Use this together with Claude to build or improve your own: share your current CV and experience, and ask Claude to apply these guidelines.

---

## 1. Section order matters

Recruiters often spend **less than 10 seconds** on a first pass. Whatever is at the top of the page decides whether they keep reading, so put your strongest, most relevant information first.

**Recommended order:**

1. **Header:** name, target title, location, contact info, LinkedIn / GitHub
2. **Intro / Profile:** a 2–3 line professional summary
3. **Skills:** a categorized tech stack
4. **Experience:** the core of the CV
5. **Side Projects** (optional)
6. **Education**

**Why this order:**

- **Skills come early** because they are the fastest way for a recruiter (or a screening system) to check that you match the role. A grouped list near the top answers "does this person have what we need?" at a glance.
- **Experience comes next** because it proves the skills. It shows you've *applied* them in real settings with real results, and it should take up most of the page.
- **Education goes last** because, once you have professional experience, your degree is a supporting detail, not your main selling point. Putting it first tells the reader "student" or "recent graduate" before they've seen what you've actually done.

> Exception: if you have no professional experience yet (e.g. you're applying for your first internship), education and academic projects can move higher. As soon as you have real experience, move education down.

---

## 2. Present yourself as a professional, not a student

- **Lead with professional experience.** It is what gets you hired, so it should take up the most space and get the most attention.
- Describe your work the way a professional would: **outcomes, ownership, and business or technical impact**, not courses taken or tasks assigned.
- Keep the education section short: degree, institution, dates, and one line of specialization at most. Leave out lists of courses and grades unless they're exceptional and relevant.
- Write the intro in a professional voice: *"AI Engineer with X years of experience building…"*, not *"Recent graduate looking for an opportunity…"*.
- **Show your strengths without stating them.** If you build things from scratch, let the bullets prove it ("designed and built…", "architected…") instead of writing "I can build from scratch".

---

## 3. Focus on experience bullet points

The experience bullets are the most important part of your CV, so spend most of your time on them.

### Keep them short

- **Keep bullets concise.** Recruiters skim, so long, wordy bullets tend to get skipped.
- **3–4 bullets per role** is usually enough. Choose your strongest 1–2 projects per role and leave out the minor ones.
- Start every bullet with a **strong action verb**: *Built, Designed, Architected, Led, Automated, Reduced, Improved, Deployed*.
- Cut filler words such as *"responsible for", "helped with", "worked on", "various", "several"*.

### Make each bullet answer these questions

- **Role / Ownership:** what *you* did (not what the team did)
- **Process / Tech:** how you did it and with which tools
- **Impact:** what changed because of your work

**Pattern:** *Action verb + what you built + with what + measurable result*

---

## 4. Use numbers to show your contribution

Numbers turn a vague claim into concrete evidence, and they make you stand out from other candidates with similar titles.

- **"Improved the pipeline"** says almost nothing.
- **"Cut pipeline runtime by 60% (5h → 2h)"** shows real, measurable impact.

**What to measure:**

- **Scale:** documents processed, requests per day, users, data volume, team size
- **Performance:** latency, accuracy, relevance, uptime
- **Efficiency:** time saved, cost reduced, manual work automated
- **Business:** revenue, project budget, clients served, adoption rate

**Rules:**

- Show **what went up or down, and by how much** (before → after when possible).
- **Never make up numbers.** If you don't have an exact figure, use an honest, defensible estimate (e.g. *"~40%"*, *"10k+"*). You may be asked about it in an interview.

### Example: too long vs. good

❌ **Too long, no numbers:**
> Worked on the development of a system that was responsible for processing documents from many different sources and using AI to extract information, which helped the team and the client to save a lot of time in their daily processes and improved the overall quality.

✅ **Short, specific, measurable:**
> Built a RAG pipeline (LangChain, FAISS) processing **500k+ documents**, cutting response latency from **4.2s to 1.6s**.

---

## 5. Keywords and ATS (Applicant Tracking Systems)

Most companies run CVs through an **ATS (Applicant Tracking System)** before any person reads them. Examples include Greenhouse, Lever, Workday and Taleo. These systems **scan your CV for specific keywords** from the job description and rank or filter candidates on how well they match. If the keywords aren't there, a person may never see your CV.

**How to write for ATS:**

- **Mirror the job description.** If the posting says *"LLM orchestration"*, *"RAG"*, *"GCP"*, use those exact terms (when they're true for you).
- **Put keywords in context.** Name tools and technologies in your bullets and tech-stack lines, not only in the skills list. Tech stacks listed per project are good keyword placements.
- **Include both the full term and the abbreviation** at least once: *"Retrieval-Augmented Generation (RAG)"*, *"Google Cloud Platform (GCP)"*.
- **Match your headline title** to the role (e.g. *AI Engineer*, *GenAI Engineer*, *ML Engineer*). Many ATS filters weigh the title heavily.
- **Keep the formatting parseable:**
  - Use standard section names (*Experience*, *Skills*, *Education*).
  - Avoid putting text inside images, icons or graphics.
  - Avoid complex multi-column layouts and tables for core content.
  - Export as a text-based PDF (one where you can select and copy the text).
- **Don't keyword-stuff.** Lists of hidden or irrelevant keywords can get flagged, and they look bad when a person does read the CV.

> Tip: paste the job description and your CV into Claude and ask it to find missing keywords and suggest where they fit *truthfully*.

---

## 6. Intro / Profile

- 2–3 lines: **title + years of experience + domains + key strengths** (e.g. working in cross-functional teams, building end-to-end systems).
- Make it specific to you. Avoid generic filler that could be on anyone's CV.
- **No hobbies or personal interests.**

---

## 7. Skills / Tech Stack

- **Group skills into categories** (e.g. *AI Engineering*, *Cloud & Infra*, *Software & Dev*, *Certifications*).
- Be specific. Categories and concrete tools stand out more than a flat list of languages.
- List only skills you can talk about confidently in an interview.

---

## 8. Side Projects

- Put minor or personal projects in a separate **"Side Projects"** section.
- Keep them **brief**, and include only ones relevant to the role you're targeting.
- Keep the whole CV **as specialized as possible**. Depth beats breadth.

---

## 9. Length and format

- **One page** unless you have 8–10+ years of experience.
- Use one consistent style throughout: same date format, same bullet style, same tense (past tense for previous roles, present tense for your current one).
- Use bold sparingly, only to help the reader's eye land on key terms and numbers.

---

## 10. Interviews: STAR method

Every bullet on your CV can come up in an interview. Prepare a structured story for each:

- **S, Situation:** the problem that needed solving.
- **T, Task:** what you set out to do (research, understanding the challenges, ideation…).
- **A, Action:** the process you followed and the tech stack you used.
- **R, Result:** the outcome and your measurable impact (the numbers from your CV).

---

## Using this project with Claude

1. Put your current CV in the project folder (LaTeX, Markdown or plain text).
2. Write a `CLAUDE.md` describing your background, target role, key strengths, and which files to keep in sync.
3. Ask Claude to review your CV against these guidelines and to **ask you for real numbers** wherever a bullet lacks them.
4. For each application, paste the job description and ask Claude to tailor your title, intro and keywords.
5. Use the STAR section to have Claude run mock interviews based on your CV.

---

## Checklist

- [ ] Section order: Header → Intro → Skills → Experience → Side Projects → Education
- [ ] Presented as a professional; education kept short and at the bottom
- [ ] Short, specific professional summary (no hobbies)
- [ ] Headline title matches the target role
- [ ] Categorized skills section near the top
- [ ] Only the strongest projects, explained clearly
- [ ] Every bullet is concise and starts with an action verb
- [ ] Role, ownership and impact clear for each project
- [ ] Numbers and metrics in most bullets (no made-up figures)
- [ ] Keywords from the job description included, written for ATS
- [ ] ATS-friendly formatting (standard headings, selectable text, no text in images)
- [ ] Key strengths shown through actions, not stated
- [ ] Fits on one page
- [ ] Ask someone to review it before sending
