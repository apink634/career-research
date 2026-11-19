# Ann Carlos · Builder's notebook

**Portfolio draft · Layout A** · [Switch to Layout B (dashboard)](portfolio-b.md) · [Project record](index.md)

> **Draft for IS218 Review 2.** Same content as Layout B, written as short project stories. Anything unfinished is labeled **in progress** or **not added yet**.

I'm a second-year Human-Computer Interaction student at NJIT and an Albert Dorman Honors Scholar. I'm interested in how technology can make people's lives easier, more fun and more meaningful, especially accessible technology and applied AI in areas like healthcare. On each project below I show the decision I made, what I compared it with and the test that checked it.

**Links:** [GitHub](https://github.com/apink634) · [LinkedIn](https://www.linkedin.com/in/anncarlos) · [Résumé draft](resume.md) · [View my code](https://github.com/apink634)

---

## Featured: Bench & Bolt repair inquiry queue (team project)

[Repository](https://github.com/apink634/is218-bench-bolt) · [Project record](https://github.com/apink634/is218-bench-bolt/blob/main/SPEC.md) · Status: **in progress** (rules and tests done; web app is the current slice)

**Problem.** A bike repair shop (simulated customer, fictional data) tracks repair requests on scraps of paper. Nothing gives them one queue or an honest status.

**What I own.** The intake form: what the coordinator enters, how errors show, and the tests for a valid submission and a blank problem. Teammates own storage (Dhruvi) and the queue page (Shree). We cross-review each other's work.

**Decision.** We chose staff-only intake over a public rider form. **Alternative:** a rider-facing form with a receipt. **Why:** the public form needs a login and a tested permission boundary, which didn't fit the term. It's kept as the "Dream."

**Second decision.** Status rules live in one explicit transition table instead of if/else checks spread across routes, so "complete a request that was never accepted" is rejected in one place.

**Check.** 18 unit tests for validation and every allowed or rejected status change pass. CI runs format, lint, types, security and tests on every pull request: [PR #4 checks, green](https://github.com/apink634/is218-bench-bolt/pull/4/checks).

---

## Word Game (individual project)

[Repository](https://github.com/apink634/word-game) · [Project site](https://apink634.github.io/word-game/) · Status: **plan stage, no code yet**

**Problem.** What's the smallest word-guessing game that's secure, keeps each player's history private and is easy to test?

**Decision.** A word-guessing game instead of a flashcard quizzer. **Why:** fixed rules are easy to test, and a bad AI hint does less damage than a wrong flashcard.

**After peer review.** A reviewer said it felt too much like Wordle ([issue #1](https://github.com/apink634/word-game/issues/1)). I'm testing one change: hints become a limited ability that costs a guess. **Check:** planned, not run.

---

## Career research

[Research site](https://apink634.github.io/career-research/) · Status: **done (Review 1)**

I compared three entry-level AI roles from the employers' own postings and chose a direction: applied AI engineering in an industry like healthcare. A peer review caught a secondary source; I replaced it with the original posting ([issue #1](https://github.com/apink634/career-research/issues/1)).

---

## Earlier work

- **GoGaia** (GirlHacks 2025): front-end developer on an AI app that identifies trash and explains how to dispose of it; designed for non-technical users. Won Best Use of Azure AI. *(Full case study not added yet.)*
- **MediPet** (Princeton IgniteSTEM 2024): companion-device concept for older adults covering medications, emergencies and isolation. 1st place of 30+ teams. *(Full case study not added yet.)*

---

## Contact

[GitHub](https://github.com/apink634) · [LinkedIn](https://www.linkedin.com/in/anncarlos) · [Résumé draft](resume.md)
