# ConceptBridge

**From Concept Gaps to Complementary Connections**

ConceptBridge is a peer-learning matchmaking system. Instead of grouping students by marks or at random, it profiles each student at the *concept level* (from quiz answers), finds pairs whose strengths and gaps complement each other, and pairs them for reciprocal teaching — one teaches what the other needs, and vice versa.

This repo contains our **two-day hackathon pilot**: a single-quiz, end-to-end vertical slice that takes a quiz → builds concept profiles → finds a reciprocal match → runs a peer-learning session → evaluates the outcome → updates learner state, and re-matches if the session didn't work.

---

## Team

**Team Name:** 404 Brain Not Found
**Track:** Semantic Matchmaking
**Institution:** Madras Institute of Technology, Anna University

| # | Name                   |
|---|------                  |
| 1 | Sanjana V (Team Leader)|
| 2 | Pragadheesh Pandian S P|
| 3 | Aishwarya N            |

---

## What This Pilot Does

1. Load one quiz (CSV) + a question-to-concept mapping
2. Score each student's proficiency per concept
3. Find a student pair with **two-way** complementary knowledge (A teaches B, B teaches A)
4. Explain the match in plain language and get mentor approval
5. Generate a short structured peer-learning session
6. Run a follow-up quiz and measure learning gain
7. Update the student's persistent profile — or re-match if the gain was too small

---

## Tech Stack (Quick View)

- **Backend:** Python
- **Data:** CSV in → JSON state out (no database)
- **LLM:** Claude API — used only for match explanations and session generation, not for scoring
- **UI:** CLI first; a small React/Vite UI if time permits


---

## Architecture



---

## Status

🚧 Project not yet started — this README will be updated as implementation progresses.
