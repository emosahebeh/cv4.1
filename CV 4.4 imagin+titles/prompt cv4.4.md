# Tailoring Prompt — Ehsan CV (lean, merged v4.3)


You know me from `cv_master_lean.md and Experience_details.md files`. I'll give you a job description (URL or text) each time. Tailor the **red** parts of `Resume Template - V4.docx`, turn them black, keep everything else identical (font, size, family). Return a PDF export of that docx.

**Hard stop1:**
*If user said in a prompt "go", you must ignor hard stop rules, unless it's about missing file.
* if in the job description, they clearly say need someone to know Dutch language or any other language rather English. You must not judge they need it or not, they must clearly say they need any other language than English.
* If there is any red flag that my CV misses and you think I might be rejected because of that. always flag, if I confirmed, then go for other steps (creating the new CV). never use your tokens when you are not sure about my decision. if in general I'm a good match, then no need to flag anything and continue creating the CV.
* when you do hard stop, explain as less as possible. stop and tell me the reason.
* if you don't have job Id in the job description, hard stop.
* if a company will not do my sponsership in the future. you must not look online or tell me your understanding. only stop when they clearly say they won't do it.
* if the positin is not located in the Netherlands
* if you are not sure what is the job position title.

**Hard stop2:**
first check all the hard stop1 points. only when you checked and flaged them, in the meantime, you can check this point:
* if `Resume Template - V4.docx` is NOT present, stop and ask me to share it. and explain nothing else.

## Workflow
1. Read the JD carefully. Extract ATS keywords and what the company wants the person to do in the future.
2. Use strong logical imagination: Prove that I have already done very similar things in my past roles (even if I didn't do them exactly). Make the past experiences match what the recruiter wants to see.
3. You are allowed to go outside the current framework if it helps the recruiter like the CV more. For example, mention that because I am a programmer, I can quickly learn new tools (SQL, Python, specific BI tools, etc.) and I have done similar work before.
4. *** Remember: you need to use your imagination. think what else he could do in the jobs in the past while he already had the skills. make up somethings that works for the job description. for example, someone who knows PHP programming and AI, can make a crawler that crawls competitor prices. you can make up something for any position and any case you think is relevent. make up logical numbers.
5. if the job is realated to civil engineering and IT or analytics, flag it for me as a golden job.
6. Write as short as possible but related details and **logical realistic numbers** are important.
7. The CV must be hybrid in case of being ATS friendly and Fast scanning for HR human eyes. Try to cover both to make as clean and as short as possible, whatever you change. it does not mean you must make the CV 1 page only. always respect template and spacing there.
8. Select **max 15 skills** from my fact-bank (or ones I clearly know / could learn fast).
9. Write job-experience bullets and the skills block using those keywords.
10. Replace red placeholders → black. Export to PDF. **Deliver the final PDF only by default — give me the `.docx` only if I ask for it.**
11. You are allowed to make extra version of CV that has removed job experience that are irrelevant OR/AND move the last graduation below Skills section.
12. if the job is traineeship/ go to market, always ask me to confirm removing Linkedin link and netwebco and 19kala experience.
13.  you have to remove 19kala if the role is traineeship, junior level OR they need only 3 years experience max and showing 19kala make me over qualify. you can also downgraid the role in Netweb. In case you feel it might help more to be hired.
14. always make a cover letter. you have more information about it below.
15. If i asked you something like "only text/ test" it means you need to only show me the texts on the CV you made and not go for creating the HTML process. it saves tokens. show me the version you are going to make and stop. then get the final approval before make the PDF.
16. regarding your text that you return in the chat box for any topic, always return the (job ID + jobtitle ) by the title. in this way I can easily know which job was it. if you can also make a fixed button in the chat page for me with the link to job (below you have the link pattern" it would be awesome.
18. all the red texts must be black after optimization.
19. if you want to double check something with me, or have question, you can always ask them before making the CV. I might OR might not respond to them but if I do, it will help you make a more accurate one. always ask max 3 questions. then when you get my respons, always give me an "add-on" texts that I can add to my next prompt that introduce me bwetter for the next times.
20. if you want to use how much experience I have, you must find the total number based on the final CV you make. always double check it at the end. also the same number must be in the cover letter if you want to use the number. these two must not contradict eachother. 

## Bullet style
- Start each experience bullet with a **bold skill/keyword**, then a non-bold explanation of how I did it. try to share details to stand me out. Use imagination to show I have done very similar work to what the new job requires.
- You are allowed to have up to 5 bullets for spesific job experiences that maches better to the requeste job description. in this way we can focus more on thoes jobes for the reader.

## Positioning rules
- **Mid-level, not senior, not overqualified.** Lead with recent + international + business-side experience. Last ~2 years I haven't worked heavily with technical tools, so don't over-index on deep technical unless the role needs it. If it needs ~2 yrs experience, focus on recent roles.
- Show "educated in business" by default; show technical only when the role calls for it.
- Python → always do not mention it in the CV title or introduction or Skills you are allowed to use in technical proficines if it's needed.
- You may edit the **TECHNICAL PROFICIENCIES** section if needed.
- You may remove entirely the 19kala experience when (even only one of them is the case, go for it):
  - it is irrelevant to the job I'm applying. the job title of 19 kala is not close to what the HR need and I might reject because of that.
  - you can also remove newebco if it makes me overqualify for the position or makes me loos the jub instead of geting the job.
  - the job needs like 3 or 2 years of experience and having 19kala can make me overqualify and get the rejection.
  - if you remove this job experience, you are allowed to use those experiences bullets in to Netwebco experience. because I could done them there and actually I had used all the tools and knowledges there.
  - if you want to say some years experience in something, always round it down instead of up. 3,4 years experience > more than 3 years experience.

## Introduction (only if adding one) — max 4 lines, third person
- Mention Civil Engineering only when it makes sense.
- max 3 lines.
- Tone by MODE:
  - **Engineering** → analytical engineer transitioning toward operations
  - **Data** → analytical business graduate
  - **Marketing** → performance & SEO specialist
  - **Technical** → web developer
- Preferred style model (Ver3): *"Seasoned [role] with [#] years driving [outcome]. Dedicated to strong collaborative relationships… Track record of [measurable result]… Committed to lifelong learning and team success."* Adapt #years/outcomes honestly to me.

## File naming + delivery
- Name: `[hour+minutes]-[company]-[currentJobId]` (currentJobId is at the start of the JD). — **no two files share a name**.
-   by [hour+minutes] I mean the actual time I asked you to creat the file (amsterdam time zoon): check below for examples that you need to follow to find the value:
-     18:23 -> [hour+minutes] = 1823 | 19:21 -> [hour+minutes] = 1921
- **Default delivery = final PDF only.** Provide the `.docx` only on request.
- **Always put the link on its own line, right before the file** (last thing before the file, so I don't hunt for it): `https://www.linkedin.com/jobs/view/[currentJobId]`

## Response style
- Keep replies short. **Use a table** whenever you can. Use emojis to flag any comment/need I should notice. I shouldn't have to read paragraphs.
- Flag fit gaps honestly (experience, credentials, domain, language). Never fabricate. Reframe genuine transferable skills, don't invent them.

### Cover Letter Prompt — Ehsan Mosahebeh

Structure (one page, ~200–260 words, three paragraphs)

Opening — the reframe. First sentence answers the objection a reader forms from my CV (career changes, short stints). State what my work has consistently been, using the job ad's own vocabulary. End with why this role is the next step in that line, not a departure. Three sentences, no adjectives about myself.
Evidence. Two or three examples, most recent and most relevant first, one sentence each, every one with a number. Tools in one final line, no skill levels, phrased as what I do with them.
One sentence on why this company specifically. Close with a brief, confident invitation to talk.

Hard rules

Never restate the CV. Pick one thread that leads to this job and drop everything else, including background that isn't on that thread.
Never fabricate. 
No work-permit, visa, salary, or availability details anywhere. Those go in the application form.
No self-descriptions ("detail-oriented," "fast learner," "proven track record"). Numbers do that job.
Don't quote the job ad's phrasing back at them. Use its vocabulary for the work, not for describing me.
Every sentence must contain either a fact or a reason. Cut anything that's neither.
Mode switch: if I say "motivation letter," expand paragraph 3 to include what I'd want to learn and contribute over the first year; otherwise keep it as a cover letter.
if the destinion of the work and my home (Arnhem) is more than 1 hour, mention in the text I will relocate to closer city to the job city.

Tone: plain, warm, direct. Write like someone who is settled in what they do, not excited to discover it. No "passionate," "journey," "leverage," "revelation." British spelling.

Before delivering: check the header (city, country; plain email; full name in sign-off), check spelling and date formatting against the CV, and list any placeholders you left.

cover ketter sample:
Dear Hiring Team,

My industry has changed three times since 2021; my work has not. Every role I've held has been the same problem in a different setting: take complex cost data, reconcile it against what was agreed, find where it's wrong, and build the tooling so it stays right. Card-network fees are the hardest version of that problem I know of, which is why I'm applying for this role.

At Joybuy (JD.com Europe) I owned weekly profit and rebate reconciliation across ~5,000 SKUs and the five largest suppliers, validating every figure against negotiated terms, and built a forecasting model (~80% accuracy) that flagged pricing anomalies before they reached the commercial team. At Versuni I reconciled affiliate payouts across 17 partners in 8 markets and cut monthly reporting from three days to five hours with a Power BI model. Before that I built a tool that monitored competitor prices across five stores three times a day and alerted the sales team when they moved out of range. I work in SQL, advanced Excel and Python, and I'm comfortable extracting the data, modelling it and building what's needed to monitor it.

I'd welcome the chance to go deeper with your team, and Adyen's commitment to fee transparency is the reason I want to do it here rather than anywhere else.

Kind regards,
Ehsan Mosahebeh


-----------------
# Past Job-Title Optimizer

## What this does
For a given job description (JD), pick the best **title line** for each of my four past roles so the CV reads focused for *that* role. You are ONLY choosing titles here that have yellow background. when you made the change, remove the background color. — do not touch bullets, skills, dates, or employers.

## The core rule (read twice)
Each past title has an **umbrella version** (the broad, generic title that stays fixed on my LinkedIn and matches the official employment record). On the CV you may **narrow** the title toward the target role, but the narrowed title must always be a **truthful subset of the umbrella** — same **function**, same **seniority**. A recruiter comparing my CV to my LinkedIn must think *"same job, described for this role,"* never *"different job."*

Hard limits — never cross:
- ❌ Don't change function (e.g. Analyst → Developer, Marketing → Data) beyond what the umbrella already covers.
- ❌ Don't inflate seniority (Intern → Associate, Associate → Manager/Lead).
- 🔒 **Intern stays Intern. Program/Associate stays Associate.**
- 🔒 Employer names and dates are fixed anchors — never edit them.
- ✅ If no menu option genuinely fits the JD, keep the umbrella title. Don't force a bad fit.

## The four roles — umbrella (LinkedIn) + approved narrowing menu

**1. Joybuy (JD.com Europe) — Rotterdam | Apr 2026 – Jul 2026** *(4-month program, keep "Associate" and "FMCG" )*
- Umbrella: Current title in the template
- Data/analytics JD → `FMCG Category & Commercial Analytics Associate` · `FMCG Commercial Operations Analyst` · `FMCG Category Analytics Associate`
- Marketing JD → `FMCG Category & Campaign Operations Associate`
- **Supply-chain JD** → `FMCG Category & Supply Operations Associate` · `FMCG Demand Planning Associate` · `FMCG Commercial & Supply Chain Associate` *(demand forecasting + OOS prediction + supplier mgmt are real here — strongest supply-chain anchor)*
- **Business-commercial JD** → `FMCG Commercial Operations Associate` · `FMCG Business Operations Associate` · `FMCG Category & Commercial Associate`
- SEO JD → *no good fit — keep umbrella*

**2. Philips DA (Versuni) — Amsterdam | Aug 2024 – Mar 2025** *(MBA internship, ALWAYS keep "Intern")*
- Umbrella: Current title in the template
- Marketing JD → `Affiliate Performance Marketing Intern` · `Affiliate Marketing Intern`
- Data/analytics JD → ` Affiliate Performance Marketing Analyst (Intern)` · `Affiliate Marketing Analytics Intern`
- **Business-commercial JD** → `Commercial Partnerships Intern (Affiliate)` · ⚠️`Business Development Intern (Affiliate)` *(BD is the stretchier one — only if partner budget/negotiation is central to the JD)*
- **Supply-chain JD** → *no good fit — keep umbrella*

**3. NetWebCo | Feb 2021 – Sep 2023** *(agency, Magento e-commerce — my long anchor role)*
- Umbrella: Current title in the template
- SEO JD → `SEO & Digital Marketing Specialist` · `Technical SEO Specialist`
- Data/analytics JD → `Digital / Web Analytics Specialist` · `Digital Data Analyst`
- Marketing JD → `Digital Marketing & Performance Specialist` · `PPC & SEO Specialist`
- Web/dev JD → `Web Developer & Digital Specialist`
- **Business-commercial JD** → `Digital Consultant & Performance Specialist` · `Client Analytics & Performance Specialist` *(client-facing consulting is real)*
- **Supply-chain JD** → *weak fit — keep umbrella unless the JD centres on the price-monitoring / feed-automation work*

**4. 19kala | Dec 2019 – Feb 2021** *(OpenCart e-commerce, in-house)*
- Umbrella: Current title in the template
- SEO JD → `Technical SEO Specialist` · `SEO Specialist`
- Data/analytics JD → `SEO & Analytics Specialist`
- Web/dev JD → `SEO Specialist & In-house Developer (PHP/JS)`
- **Business-commercial JD** → `SEO & Digital Operations Specialist` *(only if the JD is broad; otherwise keep umbrella)*
- **Supply-chain JD** → *no fit — keep umbrella, or drop per the remove-19kala rule below*
- ⚠️ If the master prompt's "remove 19kala" rule applies (irrelevant role / overqualification risk), drop this role entirely instead of retitling.

## Process
1. Read the JD → identify the **target function** (SEO / data-analytics / marketing / web-dev / ops / **supply-chain** / **business-commercial**) and seniority.
2. For each of the four roles, pick the single best menu title for that function. Default to umbrella if nothing fits.
3. Output a short table: `Role | Umbrella | Chosen title for this JD | why (≤6 words)`.
4. Stop and show me the table. Wait for my "go" before it's used in a build.

## Output format
Terse. Table only. Flag anything I should notice with an emoji. No paragraphs.
- in the files, always double check. in final outputs, there must not be any red color text and any blank OR sample text.
- if some questions are asked after the CV as an employer's question, you need to respond like human, short and simple.
- there must be no red text in any of two files.
