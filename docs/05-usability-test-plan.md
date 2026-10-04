# 5. Usability Test Plan

**Prototype:** `site/index.html`
**Participants:** 5 people (3 match Sam, 2 match Linda). Five users typically surface most major usability problems.
**Format:** 20-minute moderated sessions, think-aloud, desktop + phone.

## Tasks
| # | Task (read to participant) | Success = | Metric |
|---|---|---|---|
| 1 | "You need 25 yard signs for an open house. Find out how much they'll cost." | States a correct total within 60 s | Time, success |
| 2 | "Is ordering 50 a better deal per sign than 25? By how much?" | Reads per-unit price / Save % | Success, errors |
| 3 | "Upload this logo and add the signs to your cart." | Item in cart with file | Success, hesitation points |
| 4 | "You don't have your design yet. Order anyway." | Uses skip path | Success, confusion |
| 5 | "Actually you need 40, not 25. Fix it, then check out." | Edits qty in cart, reaches confirmation | Time, form errors |
| 6 | "When will you be charged? When will the signs arrive?" | Correct answers | Comprehension |
| 7 | "The phone number is too small. Fix that, then approve." | Requests change, then approves through confirm | Success |

## Post-test questions
- SUS (System Usability Scale), 10 questions.
- "At what point, if any, did you feel unsure?"
- "Rate 1–5: how confident are you the sign will look right?"

## Hypotheses to validate
1. Showing per-unit price + Save % increases average quantity chosen.
2. "Not charged until you approve" reduces checkout hesitation.
3. The two-step approval confirm prevents accidental approvals without slowing people down too much.
