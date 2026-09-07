# X Thread Draft: Cursor Loop

**Status:** draft. Victor posts it; this repository does not publish on anyone’s behalf.

**Evidence:** the pull request used in the original demonstration was [victorsodre/cursor-loop-demo#1](https://github.com/victorsodre/cursor-loop-demo/pull/1). Use only screenshots and links from an actual session.

## Capture the evidence

1. **Unwanted diff:** after the agent changes the wrong file, produces an out-of-scope hunk, or causes an obvious regression, capture the full diff.
2. **Clean restore:** after a restore or the chosen revert, capture the clean working tree or the restored state.
3. **Open pull request:** capture the title and short description after the real session.

An optional branch screenshot can support the third post. Do not conceal paths in a dedicated demo repository unless they contain information that should remain private.

## Draft posts

### 1. The concern

The agent changed the wrong file.
The diff was bad.
The repository was at risk.

The safeguard is not blind trust in AI.
It is a branch, a reviewed diff, and a revert you understand.

What is your safeguard today?

### 2. The rule

I drive.
The agent executes.
The work ends in a pull request.

Chat without a PR is a draft.
A PR is a receipt.

### 3. Start with a branch

Before the request: a clean branch.
A short request. A clear scope. Explicit exclusions.

An unbounded prompt is an invitation to fail quietly.

### 4. The failure

I let the agent make the change.
The diff was wrong.

I did not hide it.
I showed the problem and stopped.

Attach the unwanted-diff screenshot.

### 5. The revert

Revert.
Working tree restored.

Making mistakes cheaply lets you test more versions.
That is not bravado. It is Git hygiene.

Attach the clean-restore screenshot.

### 6. Second pass

Same goal. A narrower request.
I review each hunk and reject what does not belong.

The agent does not edit unseen.
When the work is ready, the commit gets a human message.

### 7. The pull request

Open the PR.
State what was requested, what failed, and what remained.

Attach the pull-request screenshot. Add a real link in the first reply after publication.

### 8. Habits

1. Always start with a branch.
2. Bound the request.
3. Read the entire diff.
4. Revert without drama.
5. End the loop in a PR, not a chat.
6. A silent failure usually began as a vague request.

### 9. Close

AI does not do the work for me.
It works inside a method with brakes.

If the agent damages the change, I revert it.
If it is useful, it becomes a PR.

The break stays visible with the evidence.

## Publication notes

- Do not publish from this repository.
- Prefer the three screenshots: unwanted diff, clean restore, and open PR.
- Do not cite other people as the protagonist of the method.
- Do not use unrelated Remotion, 3D, or render assets.
- Do not invent PR data. Link only a real session.
