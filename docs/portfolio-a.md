# Ann Carlos · Builder's notebook

[Projects](#projects) · [Résumé](resume.md) · [Contact](#contact) · [Project record](index.md)

I'm a second-year Human-Computer Interaction student at NJIT and an Albert Dorman Honors Scholar. I build small, tested web apps, and I'm working toward applied AI in healthcare. For each project below I show the problem, the decision I made, what I compared it with and the check that tested it. Anything unfinished is labeled.

**[View my code on GitHub](https://github.com/apink634)** · [LinkedIn](https://www.linkedin.com/in/anncarlos) · [Résumé](resume.md)

---

<a id="projects"></a>

## Featured: Diabetes questions answered from MedlinePlus (individual)

[Live app](https://rag.anncarlos.me/rag) · [Imported sources](https://rag.anncarlos.me/rag/sources) · [Code](https://github.com/apink634/my-app-studio) · Built for IS373 · Status: **working and hosted** (Build stage)

**Problem.** Someone newly diagnosed with diabetes wants plain answers, but a general chatbot can make things up. They need answers that come only from a trusted source and show where each fact came from.

**What it does.** It imports five public-domain MedlinePlus diabetes summaries and splits them into short passages. It stores each passage as an embedding and builds a small graph of facts, such as "high blood sugar causes nerve damage." Answers cite the exact passages and facts they used. Emergency questions get "call 911" without any AI call, and questions the sources don't cover get an honest "not covered."

**Decision.** Vector search plus a graph, instead of vector search alone. **Why:** a classmate's review asked which question the graph would help with. I added "Which complications are linked to high blood sugar?", which needs facts from more than one page, and its answer used graph facts.

**Checks I ran (Nov 21).** 10 of 10 graph facts matched their source quote. A repeat import created no duplicates. Six test questions, including the emergency and not-covered ones, behaved as expected. Answers survived a restart. 117 automated tests pass.

**My part.** I chose the topic, source, reader and test questions, deployed it on my own server, and ran and judged every check. An AI assistant (Claude) wrote most of the code from my plan. Limits: it knows only five pages, and AI-written answers can still be wrong, so each answer says it isn't medical advice.

---

## Bench & Bolt repair inquiry queue (team project)

[Repository](https://github.com/apink634/is218-bench-bolt) · [Project record](https://github.com/apink634/is218-bench-bolt/blob/main/SPEC.md) · Team: me, Dhruvi and Shree · Status: **plan and core rules done; web app not built yet**

**Problem.** A bike repair shop (a simulated customer with fictional data) tracks repair requests on scraps of paper. Nothing gives them one queue or an honest status.

**Decision.** Staff-only intake instead of a public rider form. **Alternative:** a rider-facing form with a receipt. **Why:** a public form needs logins and a tested permission boundary, which didn't fit the term. We kept it as the "Dream."

**My contribution.** I set up the team repository with its project record, customer kit and CI workflow. I wrote the core status rules as one transition table with their tests, with AI help, so "complete a request that was never accepted" is rejected in one place. I also synced the agreed stories and the team table ([PR #3](https://github.com/apink634/is218-bench-bolt/pull/3)) and recorded the passing CI run ([PR #5](https://github.com/apink634/is218-bench-bolt/pull/5)).

**Teammates' work.** Shree documented the customer scope and stories ([PR #2](https://github.com/apink634/is218-bench-bolt/pull/2)). Dhruvi documented the inquiry rules and workflow ([PR #4](https://github.com/apink634/is218-bench-bolt/pull/4)).

**Check.** The rules' tests pass in CI on every pull request ([PR #4 checks](https://github.com/apink634/is218-bench-bolt/pull/4/checks)).

**Next.** My slice is the intake form: what staff enter, how errors show, and tests for a valid and a blank request. *Planned, not built yet.*

---

## Word Game (individual project)

[Repository](https://github.com/apink634/word-game) · [Plan and SPEC](https://apink634.github.io/word-game/) · Status: **plan/SPEC only, no code yet**

**Problem.** What's the smallest word-guessing game that's secure, keeps each player's history private and is easy to test?

**Decision.** A word-guessing game instead of a flashcard quizzer. **Why:** fixed rules are easy to test, and a bad AI hint does less damage than a wrong flashcard.

**After peer review.** A reviewer said it felt too much like Wordle ([issue #1](https://github.com/apink634/word-game/issues/1)). I changed the SPEC so hints are a limited ability: up to 2 per round, each costing a guess.

**First check I'll run.** Duplicate-letter scoring: answer `CRANE`, guess `EERIE` must score absent, absent, present, absent, correct. *Planned, not run.*

---

## Career research

[Research and project record](index.md) · Status: **done**

I compared three entry-level AI roles using the employers' own postings and chose applied AI in an industry like healthcare. A peer review caught a secondary source, and I replaced it with the original posting ([issue #1](https://github.com/apink634/career-research/issues/1)).

---

## Earlier work

- **GoGaia** (GirlHacks 2025): front-end developer on an AI app that identifies trash and explains how to dispose of it, designed for non-technical users. The team won Best Use of Azure AI. *(Full case study not added yet.)*
- **MediPet** (Princeton IgniteSTEM 2024): a companion-device concept for older adults covering medications, emergencies and isolation. 1st place of 30+ teams. *(Full case study not added yet.)*

---

<a id="contact"></a>

## Contact

[GitHub](https://github.com/apink634) · [LinkedIn](https://www.linkedin.com/in/anncarlos) · [Résumé](resume.md) · [windyhann@gmail.com](mailto:windyhann@gmail.com)
