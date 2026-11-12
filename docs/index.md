# Career Research Site — AI Roles and My Portfolio Plan

**IS218-003 · Portfolio · Current stage: Review 1 (Plan)**

- Repository: https://github.com/apink634/career-research
- This site: https://apink634.github.io/career-research/
- My programming research site (Word Game): https://apink634.github.io/word-game/

> This is a research and planning site, not a finished portfolio. Checks are marked **planned**, **attempted** or **observed**.

---

## Research question and reader

**Question:** What do entry-level AI-related roles actually ask new graduates to do, and which of my skills and projects should my portfolio show first?

**Two reader hypotheses:**

| | Reader A: Technical hiring manager | Reader B: Campus recruiter |
|---|---|---|
| Who | An engineer screening new-grad candidates for an AI or forward deployed team | A recruiter at a career fair or scanning LinkedIn |
| Time spent | A few minutes, opens one project | Under a minute, skims the top |
| Wants to see | Working code, tests, how I made decisions | Role fit, graduation date, contact link |
| Assumption | They will click through to GitHub *(not confirmed)* | They won't read past the first screen *(not confirmed)* |

**Chosen reader:** Reader A, the technical hiring manager. My strongest evidence is project work, and that reader is the one who looks at it.

**Promise:** For a technical hiring manager on an AI or forward deployed team, this portfolio makes it easy to see a tested, secure web project I built and how I made decisions, and to contact me or open the code.

---

## Three employer sources

### 1. Forward Deployed Engineer: Palantir

| | |
|---|---|
| **Title** | Forward Deployed Software Engineer, New Grad – US Government |
| **Employer page** | [jobs.lever.co/palantir/d1ac83d0…](https://jobs.lever.co/palantir/d1ac83d0-e923-42a5-8e6d-58dd0cab25ca) |
| **Date checked** | 2026-11-11 |
| **Location** | New York, NY; on-site |
| **Eligibility** | Requires an active US security clearance or eligibility to obtain one. Graduation date: not stated. Travel 25–50% preferred. |
| **Responsibilities** | 1. Work directly with customers to find their most important problems and build solutions using their data. 2. Own projects end to end in small teams with little supervision. 3. Mix of architecture discussions, large-scale data wrangling, custom web app development and meetings with customer executives. |
| **Skill gap** | Large-scale data work and customer-facing communication. I haven't led a meeting with a real client. |

**What's new vs. familiar:** The customer-embedded part is unusual for an entry-level role. Building web apps and wrangling data is still established software work.

### 2. Other AI-related technical role: Decagon

| | |
|---|---|
| **Title** | Member of Technical Staff – New Grad (2027 Start). New grads join one of four teams: Agent Engineering, Agent Orchestration, Enterprise Product or Infrastructure. |
| **Employer page** | [jobs.ashbyhq.com/decagon/a8ff946f…](https://jobs.ashbyhq.com/decagon/a8ff946f-d6b1-4059-bc9f-fe6b11504f2f) (Decagon's own job board) |
| **Date checked** | 2026-11-12 (original page)|
| **Location** | San Francisco or New York City; on-site |
| **Eligibility** | B.S. or higher in CS or a related field, graduating between December 2026 and July 2027. Work authorization: not stated. Pay: $185K base salary plus equity. |
| **Responsibilities** | 1. Own work end to end on systems behind Decagon's AI agents. 2. On Agent Engineering: deploy AI agents for customers and collaborate directly with them on scalable solutions. 3. Dig into system failures across deep technology stacks. |
| **Skill gap** | Asynchronous programming and TypeScript; I mostly use Python. The posting also asks for experience using AI coding agents in development, which I'm starting in this course. |

**What's new vs. familiar:** "Member of Technical Staff" is a vague title, and asking new grads for AI coding-agent experience is new. Debugging, Python and shipping features are established software work. The Agent Engineering team's customer collaboration overlaps with FDE work.

### 3. AI role in another industry (healthcare): Premise Health

| | |
|---|---|
| **Title** | Associate AI Engineer (Req. 38467) |
| **Employer page** | [internaljobs.premisehealth.com/…/associate-ai-engineer](https://internaljobs.premisehealth.com/job/brentwood/associate-ai-engineer/27229/92130846032) |
| **Date checked** | 2026-11-11 |
| **Status** | Probably closed. The page said it was expected to close within 90 days of 02/25/2026. Kept as an example of the role type. |
| **Location** | Brentwood, TN or remote |
| **Eligibility** | Bachelor's in CS, AI, EE or related; 0–2 years experience. Work authorization and travel: not stated. |
| **Responsibilities** | 1. Support ML deployments and API development under senior guidance. 2. Help build AI/ML workflows for production applications. 3. Explain AI capabilities and limitations to stakeholders. |
| **Skill gap** | Healthcare data experience (preferred) and cloud platforms such as Azure, AWS or Databricks. |

**What's new vs. familiar:** Explaining AI limits to non-technical staff is a new emphasis. APIs, Python and Docker are established software skills, and they overlap with what IS218 covers.

---

## Facts, interpretations and assumptions

- **Facts:** All three roles ask for programming (Python appears in each). Two of three mention working directly with customers or stakeholders. The Palantir role requires security clearance eligibility.
- **Interpretation:** "AI engineer" titles at the entry level still look mostly like web, API and data work, plus communication.
- **Assumptions:** That these three postings are typical *(only three, not a survey)*. That projects with tests carry weight with technical readers *(not confirmed)*.

---

## Two career directions

| | Direction 1: Customer-facing AI deployment (FDE-style) | Direction 2: Applied AI engineering in an industry (e.g., healthcare) |
|---|---|---|
| Based on | Palantir, Decagon | Premise Health |
| Daily work | Building with and for customers, often on-site | Building AI workflows inside one organization |
| What I'd need | Communication, fast end-to-end builds, travel | Domain knowledge, cloud platforms, reliability |
| Fit with my current work | Strong. The word-game project is an end-to-end build. | Partial. No domain experience yet. |

**Main direction for the portfolio:** Direction 2
**Next learning step:** Finish the word-game AI hint experiment and write up the evaluation

---

## Brand and layout

**Voice words:** clear, curious, practical *(edit to fit you)*
**Brand character:** a careful builder who shows their work

**Two layout directions.** Both share the same intro, projects and main action ("View my code / Contact me").

| | Direction A: Builder's notebook | Direction B: Clean project dashboard |
|---|---|---|
| Feel | Warm, written, like lab notes | Minimal, card grid, quick to scan |
| Intro | Short paragraph about what I build and why | One line plus role tags |
| Projects | Each project as a short story: problem, decision, test | Each project as a card: title, stack, link |
| Best for | Reader A (hiring manager who reads) | Reader B (recruiter who skims) |
| Accessibility | Readable text size, keyboard-reachable links *(planned check)* | Same *(planned check)* |

**Visual reference:** (https://webdesign.kernjosh.com/)

**Leaning toward:** Direction A, because it matches the chosen reader.

---

## Short spec: stories

1. **As a hiring manager, I want to see what the candidate builds within 10 seconds.**
   Check: the top of the page names my role focus and links one featured project without scrolling. *(planned)*
2. **As a hiring manager, I want to open the code for a project.**
   Check: each project has a working GitHub link. *(planned)*
3. **As a hiring manager, I want to see how the candidate made decisions.**
   Check: the featured project shows one decision, the alternative I considered and the test that checked it. *(planned)*
4. **As a keyboard user, I want to reach every link.**
   Check: tabbing through the page reaches every link in order with a visible focus outline. *(planned)*
5. **As a recruiter, I want to contact the candidate.**
   Check: a contact link or LinkedIn link is visible on the first screen. *(planned)*

---

## AI assistance

- **Tool:** Claude (Anthropic)
- **Used for:** finding the three postings, summarizing their pages, and drafting this page's structure and comparison.
- **Verification:** I opened each employer page myself and confirmed the title, eligibility and responsibilities. Results: First two confirmed on the employer's own page on 2026-11-12; third link shows that job posting is closed
- **Correction after peer review:** My first draft used secondary job listings for Decagon. After [issue #1](https://github.com/apink634/career-research/issues/1), I replaced them with Decagon's original posting. The earlier secondary summary had described a different, closed role (Agent Software Engineer, 2026 Start), so those responsibilities were removed.

---

## Partner review

| Reviewer | Date | What they tried | Feedback | Issue | Decision |
|---|---|---|---|---|---|
| dhruvi0805 | 2026-11-12 | Read the employer sources and AI assistance section | Decagon still relied on secondary sources, and verification results were blank | [#1](https://github.com/apink634/career-research/issues/1) | **Implement**, because original sources are required. Replaced Decagon info with the original posting and filled in verification.Reviewer rechecked 2026-11-12 and confirmed. Issue closed.|

---

## Next step

Choose the main direction, confirm the Decagon posting on the original page, and pick a visual reference before the Build stage.
