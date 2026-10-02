# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
“I'm learning AI engineering because I'm already using it daily and I need to level up my skill.” I'm a RevOps person viewed as technical, with experience building through AI coding tools, low-code automation, system configuration, and APIs. I want to understand technical system design and pitfalls, and build more durable, faster products with less refinement.

My first build goal is an agent using a RAG product. My side project is a better badge-scanning app using ASR and OCR to capture leads at events. I want both a user-facing tool with prompt-configured CRM connections and an integration that customers' own agents can configure and use within their systems.

Immediate priorities: project planning with AI, architecture judgment, Git, CI/CD, and reliable delivery. Start at 2 hours/week; potentially increase to 5. Prefer quick practical improvements applied to my projects, with planning habits useful beyond coding.

Tutor guidance: distinguish AI foundation placement from software engineering ability. The quiz does not assess architecture, Git, CI/CD, or AI-assisted project planning. Preserve the foundation route below, but offer targeted practical sessions early rather than treating all model-training material as a prerequisite for these goals. Do not mark skipped or unstudied lessons as mastered.

Practical lesson candidates:
- [Phase 0, lesson 02: Git & Collaboration](phases/00-setup-and-tooling/02-git-and-collaboration/docs/en.md). Prerequisite: Phase 0 lesson 01. Although Phase 0 is Skip under the placement rubric, this individual lesson addresses an explicitly stated gap.
- [Phase 14, lesson 43: Frame the Task Before the Agent Writes Code](phases/14-agent-engineering/43-frame-the-task-before-code/docs/en.md). Prerequisites: Phase 14 lessons 31 and 36. Use a bounded badge-scanner or RAG-agent change as the exercise.
- [Phase 14, lesson 44: Build an Evidence-Backed Execution Plan](phases/14-agent-engineering/44-plan-from-evidence/docs/en.md). Prerequisite: lesson 43. Produce a reusable plan with dependencies and acceptance evidence.

CI/CD and broader architecture remain learning priorities; select suitable lessons when those sessions begin. Git & Collaboration core instruction and guided practice completed on 2026-10-01; closing assessment was only partially scored because two questions covered material not yet taught.

## Placement
- Date: 2026-09-30
- Score: 3/10 — Math & Statistics 0/2; Classical ML 0/2; Deep Learning 0/2; NLP & Transformers 1/2; Applied AI 2/2.
- Entry point: Phase 1: Math Foundations
- Pace: ~2 hours/week initially; potentially 2–5 hours/week later.
- Answers: Q1 not sure; Q2 A; Q3 not sure; Q4 not sure; Q5 not sure; Q6 not sure; Q7 not sure; Q8 B; Q9 A; Q10 B.
- Interpretation: Foundation recommendation from the course rubric. Applied AI concepts are stronger than math and model-training foundations; this short quiz does not establish practical mastery.

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Skip | -- |
| 1 | Math Foundations | Do | 23 |
| 2 | ML Fundamentals | Do | 21 |
| 3 | Deep Learning Core | Do | 15 |
| 4 | Computer Vision | Do | 27 |
| 5 | NLP | Do | 30 |
| 6 | Speech & Audio | Do | 18 |
| 7 | Transformers Deep Dive | Do | 14 |
| 8 | Generative AI | Do | 14 |
| 9 | Reinforcement Learning | Do | 13 |
| 10 | LLMs from Scratch | Do | 26 |
| 11 | LLM Engineering | Do | 19 |
| 12 | Multimodal AI | Do | 65 |
| 13 | Tools & Protocols | Do | 43 |
| 14 | Agent Engineering | Do | 55 |
| 15 | Autonomous Systems | Do | 20 |
| 16 | Multi-Agent & Swarms | Do | 28 |
| 17 | Infrastructure & Production | Do | 32 |
| 18 | Ethics, Safety & Alignment | Do | 31 |
| 19 | Capstone Projects | Do | 620 |

Total estimated Review + Do time: ~1114 hours across 19 phases, using ROADMAP.md estimates. This is the full curriculum, including 620 capstone hours, not the time required to improve the current projects. Targeted lessons above are included in phase estimates except the skipped Phase 0 refresher. No Review rows apply because both NLP phases are already Do.

### Next session handoff — 2026-10-02

The **GitHub pull requests and code review** session is complete: practice branch `learning/pr-review` created and pushed with `-u`; PR #1 opened via `gh pr create` on the learner's own fork, targeting that fork's `main`; **merged** (merge commit `ccb6ac88`). The learner fast-forward pulled the PR merge down and completed a full upstream sync (fetch upstream → merge upstream/main → push to fork). A push-rejection caused by skipping the pull step was hit and diagnosed live. Next practical session: the PR review loop below; after that, return to Phase 1 foundation route.

Teach interactively here in chat; no advance website reading is expected. The learner runs terminal commands with `!`, and their command output appears in the conversation. Explain unfamiliar commands and flags before using them, pause for predictions, and assess only material actually taught.

Next exercise, confined to the learner's fork (PR #2, ~10 minutes):
1. Branch `learning/pr-review-2`, make one small change (e.g. append a line to `learning-pr-practice.md`), commit, push.
2. Open PR #2 via `gh pr create` against the fork's `main`.
3. Leave a line comment on the changed file in the diff; explain line comments versus general discussion, and that GitHub does not let an author approve their own PR.
4. Make a follow-up commit responding to that comment, push, and observe the existing PR update automatically — no new PR needed.
5. Discuss CI checks (the repo's curriculum workflow runs on PRs) and merge choices at beginner level; merge PR #2.
6. Pull the result locally, optionally delete the practice branch (local and remote with `git push origin --delete`).

Local `main` carries PR #1's merge (`ccb6ac88`) plus the upstream course merge, and is pushed to `origin/main`. `learning-pr-practice.md` exists on `main`; branch `learning/pr-review` exists locally and on the fork. GitHub auth works via `gh` (keyring token, account `adamchu22`). Fork sync ladder the learner can now run independently: `git checkout main` → `git pull` → `git fetch upstream` → `git merge upstream/main` → `git push`.

The `.claude/skills/` entries were symlinks into `.agents/skills/` (a multi-harness skill-manager setup from 2026-09-30) sitting on Git-tracked paths, so every operation that tried to snapshot the worktree failed with "beyond a symbolic link" and blocked merges. Fixed on 2026-10-02: links deleted, tracked files restored with `git checkout -- .claude/skills`, handoff committed. The `.agents/skills/` copies were left intact. If the skill manager re-creates the links and pulls break again, reconcile the manager/skills-lock config rather than hiding paths from Git.

The learner understands branch versions, local versus remote history, staging snapshots, `checkout -b` versus `checkout`, fetch versus pull, fast-forward pulls, and why push rejects when the remote is ahead. The tutor introduced `checkout -b` and model file formats only after unfair quiz questions; do not record those as incorrect independent assessments. Still needs hands-on practice: line comments and reviews, follow-up commits on a live PR, CI checks, merge styles, and PR branch cleanup.

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-10-01 | 00-setup-and-tooling/02-git-and-collaboration | 1/1 fairly assessed; 2 further questions explained, unscored | Requested detour from foundation route. Completed staging, commits, branch switching, fast-forward merge, fork/remotes, and push. Corrected push-before-commit confusion. Covered ignore/untracking conceptually; no ignore-file exercise run. Tutor introduced checkout -b and model file formats only after quiz questions; revisit these in a future warm-up without treating this as learner failure. |
| 2026-10-02 | GitHub PR & code-review practice (tutor-directed extension) | — | Opened PR #1 via `gh pr create` on own fork and merged it; learned push ≠ PR creation and PRs live at repo level; fast-forward pull brought the merge down; diagnosed self-caused push rejection (skipped pull); learned fetch vs pull and per-branch sync; synced fork with upstream. Fixed `.claude/skills` symlink collision that blocked all merges. |

## Review queue

