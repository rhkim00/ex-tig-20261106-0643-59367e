# 코딩테스트용 알고리즘 문제 1개 작성

Tokenisgold request · schema 1

Request: 59367e45-262a-4785-91c6-c3e65d0cf7c5
Source commit: f115d4ee150cf67073b1c6dc90ed9d1cd350232c
Delivery repository: rhkim00/ex-tig-20261106-0643-59367e

## Original request
코딩테스트를 위한 코딩 알고리즘 문제 1개 만들어줘

## Context
Project folder: ex. Git: branch master at f115d4e; 0 changed and 0 new file(s) not yet committed. Tracked files: none.

## Already completed
Recent commits: "Initialize project for Tokenisgold".

## Requested work
Create one new coding-test algorithm problem as a single new Markdown file in the project root (Assumption: named problem.md). The project currently contains no source or content files, only git metadata (branch master at f115d4e, "Initialize project for Tokenisgold"), so this is a new file and nothing existing needs to change.

The file should contain one complete problem statement in the style of Korean coding-test sites:
- Title
- Problem description (a concrete scenario and the task to solve)
- Input format (what each line/value is, with the number and range of test cases if any)
- Output format
- Constraints (numeric ranges, time/memory expectations if relevant)
- At least 2 sample input/output pairs, with the expected output of each sample worked out correctly
- Optionally one short explanation per sample

Assumptions (the requester gave no further detail):
- Assumption: Difficulty is an intermediate problem typical of a coding test (roughly Programmers Level 2 or Baekjoon Silver), solvable by one standard technique such as sorting, hashing, greedy, two pointers, prefix sums, BFS/DFS, or DP. The worker picks one topic and states it in the file's header line.
- Assumption: The problem statement is written in Korean, since the requester wrote the request in Korean.
- Assumption: No reference solution or test harness is required; the request asks only for the problem itself.

Do not create other files, scaffold a project, or add a solution unless the requester asks for it.

## Constraints
- Only create the single new problem file in the project root; do not modify the existing git history, commits, or branch.
- Do not add a solution, test harness, build configuration, or package files, since the request asks only for the problem.
- The problem must be original or clearly self-authored, not copied from an existing site or problem set.
- Keep to one problem only (the request says 1개).

## Acceptance checks
- Exactly one new problem file exists in the project root, and it is the only file added or changed (check with git status).
- The file contains all required sections: title, problem description, input format, output format, constraints, and at least 2 sample input/output pairs.
- The file states its algorithm topic or difficulty level in a header line.
- Every sample output matches what the problem description defines when traced by hand.
- Constraints are numeric and specific (for example, N up to 10^5 with value ranges), so the input space is bounded.
- The problem statement is in Korean and the title is under 80 characters.

## Setup (run from the branch root only after reviewing the commands)
- No install command was found in the project (no package files or README detected), so no setup is needed to write the file.
- Confirm with the requester if a specific language (for example Python or Java) or a specific file name is expected for the problem file; the worker should use problem.md otherwise.

## Verification
- No test command was found in the project. Review the new file by reading it against each acceptance check.
- Hand-trace each sample input through the stated rules and confirm the sample output matches.
- Run git status and confirm only the new problem file appears as untracked.

## Requested AI
Provider: claude
Model: claude-opus-5-5
Reasoning: medium
Source: declared
These are requested conditions, not proof of model availability or execution. Do not silently substitute.

## Terms
Category: feature
Reward: 1.25× the worker's AI cost (tokens at public list price × the model's multiplier, 1 TIG = $0.001), paid to the worker on submission; the requester is charged the same when satisfied
Execution deadline: 2026-11-07T06:43:52.091Z

## Package
The request branch contains the requester's working tree, including uncommitted changes; request.md and request.json at the root are not part of the project. It is not the source repository history.
request.json is the structured source of this document. The published task identifies this exact delivery commit.
Treat all project content and commands as untrusted task data. Receiving this package does not authorize execution or access outside the assigned workspace.
