# YouTube Briefing: Cursor Loop

## Editing code with Cursor: branch, revert, pull request

**Target length:** 12–18 minutes, shortened if the honest material is shorter. The initial recording may be in Brazilian Portuguese with English subtitles in the description. The demonstration is the on-screen subject; it does not require a talking-head segment.

**Publication status:** draft only. Do not upload or publish from this document.

## Core statement

> I drive. The agent executes. The work ends in a pull request. If it breaks, I revert it.

The episode should show that a branch and a reversible workflow reduce the cost of trying an agent-assisted change. It should not claim that an agent is inherently reliable.

## Required evidence

Record a real session before filming:

- A clean branch created from main.
- One unwanted agent edit: wrong file, out-of-scope diff, or visible regression.
- One restore or revert, including the resulting repository state.
- One pull request containing the approved path.
- Real links and hashes only. Do not invent a pull-request number.

If any evidence is staged for teaching, disclose it on screen. A real failed session is preferable.

## Recording outline

1. **Open on the defect (0:00–0:40).** Show the unwanted diff in full screen. Pause, then state that it came from the agent.
2. **State the concern (0:40–2:30).** Editing with an agent can damage a repository; a branch and revert provide the safety rail.
3. **Give the rule (2:30–4:00).** “I drive. The agent executes. The work ends in a pull request.”
4. **Create the branch (4:00–6:00).** Show a clean Git status, a new branch, and a bounded request: target file, scope, and exclusions.
5. **Show the unwanted edit (6:00–9:00).** Explain the concrete mismatch without presenting it as a success.
6. **Revert cleanly (9:00–11:30).** Show the command and the cleaned state. Explain that a lower cost of failure makes experimentation practical.
7. **Make a second pass (11:30–14:30).** Narrow the request, review the diff line by line, and accept only what meets the goal.
8. **Open the pull request (14:30–16:30).** Show a concise title and description: requested work, observed failure, and final result.
9. **Close with habits.** Branch first; bound the request; read the full diff; revert without drama; finish in a PR; treat silent failure as a vague request.

## Suggested B-roll

1. Full-screen unwanted diff.
2. Git status and the new branch.
3. The bounded Cursor request.
4. Side-by-side: unwanted diff and clean state after restore.
5. Second-pass hunk review.
6. Pull-request screen or the real flow to create it.
7. A plain card listing the six habits.

## Editorial constraints

- Do not use invented statistics, pull-request numbers, or fabricated outcomes.
- Do not claim that “Composer solved it.”
- Do not turn another person’s handle into the protagonist.
- Do not use unrelated Remotion, 3D, or render material.
- Do not end by claiming that the workflow was perfect.
- Use the pull request as evidence, not as a popularity claim.

## Pre-recording checklist

- [ ] Real branch, unwanted edit, restore/revert, and PR completed.
- [ ] Real links and hashes added where shown.
- [ ] Thumbnail draft approved by Victor.
- [ ] The ten-beat outline is recordable.
- [ ] No unrelated visual assets in the edit.
