# Elaine SAT Reading and Writing Workspace

Student-facing GitHub Pages portal for Elaine's SAT Reading and Writing course.

## Routes

- `/` — learner workspace: Class Logbook (empty until the first lesson), Mock Practice, Target Practice, Mistake Logbook
- `/mock-1/` — Mock 1 (August 22 Test Set), 54 Reading and Writing questions in two modules with draft saving and a deliberate submit button
- `/boosters/skill-booster/` — Target Practice hub: Intensive Skill Booster across four domains and ten question types
- `/boosters/skill-booster/<domain>/` — one page per SAT domain listing its practice sets
- `/boosters/skill-booster/practice/<question-type>-<n>/` — one practice set with automatic checking after a deliberate submit
- `/mistake-log/` — server-backed Mistake Logbook with checked mistakes and retry states

## Access and privacy

The learner enters the course password once in a browser. A successful entry stores an opaque trusted-browser credential—not the password—and silently renews short-lived access on later visits. A new browser or device, private browsing, or cleared site data requires the password again.

The Teacher Portal remains Google owner-only and never asks the teacher for Elaine's password.

The repository and static question assets are public, so answer keys, teacher notes, source maps, internal question IDs, learner responses, scores, and private records stay outside this repository. All learner routes use `noindex` metadata. Mock and practice pages preserve drafts and require a visible learner-controlled submit action.
