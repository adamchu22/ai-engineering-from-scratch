# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
“I'm learning AI engineering because I'm already using it daily and I need to level up my skill.” I'm a RevOps person viewed as technical, with experience building through AI coding tools, low-code automation, system configuration, and APIs. I want to understand technical system design and pitfalls, and build more durable, faster products with less refinement.

My first build goal is an agent using a RAG product. My side project is a better badge-scanning app using ASR and OCR to capture leads at events. I want both a user-facing tool with prompt-configured CRM connections and an integration that customers' own agents can configure and use within their systems.

Goal statement refined 2026-10-05 (learner's own words): become better at vibe coding, agent building, and infrastructure design fundamentals, to build better products and services. The plan is built from that statement; theory phases are chosen on demand, never as a gate.

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

**Plan v2 — rewritten 2026-10-05 at the learner's direction.** Goal: build better products and services — vibe coding, agent building, infrastructure design fundamentals. Theory-heavy phases are deliberately skipped; cherry-picking across phases matches how the site's own learning paths are built. The original placement-driven foundation table is retired (learner chose practical-first after reviewing the site's learning paths).

| Order | Phase | Slice | Status | Est. hours |
|-------|-------|-------|--------|------------|
| 1 | 00 Setup & Tooling | all 11 lessons (02-Git done 2026-10-01) | In progress | ~11 |
| 2 | 01 Math Foundations | 01-linear-algebra-intuition done (2026-10-05, 3/3) + 4 confirmed must-do lessons below | In progress | ~4 |
| 3 | 02 ML Fundamentals | 3 must-do lessons (confirmed below) | Planned | ~4 |
| 4 | 09 Reinforcement Learning | 2 must-do lessons (confirmed below) | Planned | ~2 |
| 5 | 10 LLMs from Scratch | 10-evaluation, 14-open-models; optional 11-quantization, 12-inference-optimization | Planned | ~3 |
| 6 | 11 LLM Engineering | all 17 lessons | Planned | 19 |
| 7 | 13 Tools & Protocols | all 31 lessons | Planned | 43 |
| 8 | 14 Agent Engineering | all 54 lessons; recommended spine = `using-coding-agents` path (16 lessons, ~15h), then the rest by interest | Planned | 55 |
| 9 | 15 Autonomous Systems | split confirmed: 9 build-critical lessons, 13 to reading list | Planned | ~6 |
| 10 | 16 Multi-Agent & Swarms | all 25 lessons | Planned | 28 |
| 11 | 17 Infrastructure & Production | all 28 lessons | Planned | 32 |
| 12 | 19 Capstone Projects | learner's shortlist (see below) | Planned | — |

### Order to teach — top to bottom, one by one (Plan v3, 2026-10-08; finishes current phase before next unless learner says skip)
- [x] 00/01 dev-environment — done 3/3 on 2026-10-08
- [x] 00/02 git-and-collaboration — done 2026-10-01
- [ ] 00/03 gpu-setup-and-cloud — done 3/3 on 2026-10-08 (Mac: no nvidia-smi, cuda False / mps True; Rust 1.99 + Julia 1.13.1 installed; CPU bench 0.01s @1500)
- [ ] 00/04 apis-and-keys — NEXT
- [ ] 00/05 jupyter-notebooks
- [ ] 00/06 python-environments
- [ ] 00/07 docker-for-ai
- [ ] 00/08 editor-setup
- [ ] 00/09 data-management
- [ ] 00/10 terminal-and-shell
- [ ] 00/11 linux-for-ai
- [ ] 00/12 debugging-and-profiling
- [x] 01/01 linear-algebra-intuition — done 3/3 on 2026-10-05
- [ ] 01/02 vectors-matrices-operations — paused 2026-10-08 at learner request, not mastered
- [ ] 01/10 dimensionality-reduction
- [ ] 01/14 norms-and-distances
- [ ] 01/06 probability-and-distributions
- [ ] 02/01 what-is-machine-learning
- [ ] 02/08 feature-engineering
- [ ] 02/09 model-evaluation
- [ ] 09/01 mdps-states-actions-rewards
- [ ] 09/09 reward-modeling-rlhf
- [ ] Phase 10: 10-evaluation, 14-open-models (11, 12 only if build needs it)
- [ ] Phase 11: all 17 lessons
- [ ] Phase 13: all 31 lessons
- [ ] Phase 14: all 54 lessons
- [ ] Phase 15 keep as lessons: 01, 09, 10, 11, 12, 13, 14, 15, 16 (rest reading list)
- [ ] Phase 16: all 25 lessons
- [ ] Phase 17: all 28 lessons
- [ ] Phase 19: learner shortlist only

### Must-do lessons (confirmed by learner 2026-10-05)

**Phase 01 — math that pays rent in the phases above:**
- [02-vectors-matrices-operations](phases/01-math-foundations/02-vectors-matrices-operations/docs/en.md) — the working mechanics under every embedding and model layer.
- [10-dimensionality-reduction](phases/01-math-foundations/10-dimensionality-reduction/docs/en.md) — PCA etc.; inspecting/visualizing embeddings when building RAG and eval dashboards.
- [14-norms-and-distances](phases/01-math-foundations/14-norms-and-distances/docs/en.md) — cosine/L2 distance; the arithmetic RAG runs on every retrieval call.
- [06-probability-and-distributions](phases/01-math-foundations/06-probability-and-distributions/docs/en.md) — makes temperature, sampling, and eval metrics readable.

**Phase 02 — the practical ML spine:**
- [01-what-is-machine-learning](phases/02-ml-fundamentals/01-what-is-machine-learning/docs/en.md) — vocabulary shared with 10/06-SFT and every eval discussion.
- [08-feature-engineering](phases/02-ml-fundamentals/08-feature-engineering/docs/en.md) — turning domain knowledge into structured inputs; the same muscle as context engineering.
- [09-model-evaluation](phases/02-ml-fundamentals/09-model-evaluation/docs/en.md) — precision/recall/F1/ROC/confusion matrix — the most load-bearing lesson for the eval-heavy capstones.

**Phase 09 — only two lessons:**
- [01-mdps-states-actions-rewards](phases/09-reinforcement-learning/01-mdps-states-actions-rewards/docs/en.md) — the state/action/reward vocabulary behind every agent design.
- [09-reward-modeling-rlhf](phases/09-reinforcement-learning/09-reward-modeling-rlhf/docs/en.md) — how models get tuned to be helpful; pairs with 10/08-DPO when fine-tuning comes up.

**Phase 15 split (confirmed):**
- Keep as lessons: 01-long-horizon-agents, 09-coding-agent-landscape, 10-claude-code-permission-modes, 11-browser-agents, 12-durable-execution, 13-cost-governors, 14-kill-switches-canaries, 15-propose-then-commit, 16-checkpoints-rollback.
- Reading list (frontier/safety case studies, low direct build value): 02, 03, 04, 05, 06, 07, 08, 17, 18, 19, 20, 21, 22.

**Optional later (pull only when a build demands it):** 01/05-chain-rule-and-autodiff (before any training-loop capstone), 01/09-information-theory, 01/12-tensor-operations, 01/13-numerical-stability, 02/02-linear-regression, 02/03-logistic-regression, 02/06-knn-and-distances, 02/07-unsupervised-learning, 02/10-bias-variance, 02/13-ml-pipelines, 02/17-imbalanced-data, 10/11-quantization, 10/12-inference-optimization.

Standing rule from placement, unchanged: never mark skipped or unstudied lessons as mastered.

### Next session handoff — 2026-10-02

The **GitHub pull requests and code review** session is complete: practice branch `learning/pr-review` created and pushed with `-u`; PR #1 opened via `gh pr create` on the learner's own fork, targeting that fork's `main`; **merged** (merge commit `ccb6ac88`). The learner fast-forward pulled the PR merge down and completed a full upstream sync (fetch upstream → merge upstream/main → push to fork). A push-rejection caused by skipping the pull step was hit and diagnosed live.

### Next session handoff — 2026-10-05

Phase 1 lesson 01 (Linear Algebra Intuition) taught interactively; quiz passed 3/3. Teaching notes: matrix concept needed one re-explanation — learner explicitly wants **ASD-STE100-style controlled definitions** (plain words, short sentences, arithmetic first, geometry vocabulary only as a label after the computation is owned). That sequence worked: dot product → matrix@vector → "one dot product per row" → rank via build-from → NumPy use-it all landed. Learner independently synthesized: training = per-number nudges, model memory = table numbers, retrieval = dot products. Scratch scripts ran live under `/tmp/` (Python 3.14, NumPy 2.4.6; Julia not installed — Julia lesson blocks skipped).

Warm-up partially completed: PR #2 on the fork went through branch, commit, push with `-u`, `gh pr create`, and merge — but the **line-comment → follow-up-commit → CI-checks → merge** loop was skipped (PR merged early; 0 comments, 0 reviews). Two gotchas taught: `gh` defaults to the parent repo (rohitg00's) in fork setups, so `--repo adamchu22/ai-engineering-from-scratch` is mandatory; PR numbers are per-repo, not global.

**Next lesson:** 00/04 apis-and-keys (00/03 done 3/3).

Teach interactively here in chat; no advance website reading is expected. The learner runs terminal commands with `!`, and their command output appears in the conversation. Explain unfamiliar commands and flags before using them, pause for predictions, and assess only material actually taught.

Completed 2026-10-08 as PR #3 (branch `learning/pr-review-3`, merged as `e418a556`): line comment left on the diff, follow-up commit pushed (PR auto-updated 1→2 commits), CI checks discussed (path-filtered workflow → zero checks on practice files is correct), merged, branches deleted local + remote.

Local `main` carries PR #1 (`ccb6ac88`), PR #2 (`200bbf46`), and PR #3 (`e418a556`) merges plus the upstream course sync, and is pushed to `origin/main`. No practice branches remain (local or remote). GitHub auth works via `gh` (keyring token, account `adamchu22`). Fork sync ladder the learner can now run independently: `git checkout main` → `git pull` → `git fetch upstream` → `git merge upstream/main` → `git push`.

The `.claude/skills/` entries were symlinks into `.agents/skills/` (a multi-harness skill-manager setup from 2026-09-30) sitting on Git-tracked paths, so every operation that tried to snapshot the worktree failed with "beyond a symbolic link" and blocked merges. Fixed on 2026-10-02: links deleted, tracked files restored with `git checkout -- .claude/skills`, handoff committed. The `.agents/skills/` copies were left intact. If the skill manager re-creates the links and pulls break again, reconcile the manager/skills-lock config rather than hiding paths from Git.

The learner understands branch versions, local versus remote history, staging snapshots, `checkout -b` versus `checkout`, fetch versus pull, fast-forward pulls, and why push rejects when the remote is ahead. The tutor introduced `checkout -b` and model file formats only after unfair quiz questions; do not record those as incorrect independent assessments. Still needs hands-on practice: merge styles (only merge-commit used so far; squash/rebase untouched).

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-10-01 | 00-setup-and-tooling/02-git-and-collaboration | 1/1 fairly assessed; 2 further questions explained, unscored | Requested detour from foundation route. Completed staging, commits, branch switching, fast-forward merge, fork/remotes, and push. Corrected push-before-commit confusion. Covered ignore/untracking conceptually; no ignore-file exercise run. Tutor introduced checkout -b and model file formats only after quiz questions; revisit these in a future warm-up without treating this as learner failure. |
| 2026-10-02 | GitHub PR & code-review practice (tutor-directed extension) | — | Opened PR #1 via `gh pr create` on own fork and merged it; learned push ≠ PR creation and PRs live at repo level; fast-forward pull brought the merge down; diagnosed self-caused push rejection (skipped pull); learned fetch vs pull and per-branch sync; synced fork with upstream. Fixed `.claude/skills` symlink collision that blocked all merges. |
| 2026-10-05 | 01-math-foundations/01-linear-algebra-intuition | 3/3 | First foundation lesson. Hit a wall on "matrix as transformation" metaphors — re-taught with controlled language (ASD-STE100 style): matrix = table, op = dot each row, geometry words as labels afterward. Then ran everything by hand and in NumPy. Strong self-synthesis of training-as-number-nudging. LoRA taught just-in-time before quiz (rank was taught in-session; LoRA was not). Warm-up PR #2 merged early, skipping the comment/CI practice — parked as PR #3 for next session. Quiz option A flagged as too dense by learner; keep quiz phrasing plainer going forward. |
| 2026-10-08 | GitHub PR #3 full review loop (tutor-directed extension) | — | Branch `learning/pr-review-3`, 2 commits; line comment vs general discussion taught and practiced; author-approval block noted; follow-up commit auto-updated the PR; CI path-filter lesson (zero checks on practice files is correct); merged (`e418a556`); pulled; deleted branch local + remote. Plan v2 committed in the same session. |
| 2026-10-08 | 00-setup-and-tooling/01-dev-environment | 3/3 | Python 3.14.7, Node v22.22.3, uv + pnpm present, NumPy 2.4.6, torch 2.13.0. Built `/tmp/env-demo` venv with uv, proved isolation (system has NumPy, venv does not). MPS check True + test tensor op (sum 9.0). Rust + Julia deferred (install when a later lesson needs them). Quiz: venv why, layer order, MPS check — all correct. |

## Review queue

