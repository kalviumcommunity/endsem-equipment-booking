# End Semester Examination, Set 1, Question 1
# Integrate Equipment Booking Guide Updates

**Total: 30 marks | Submit one PDF**

## Problem

Two contributors updated an equipment booking guide. Their cancellation instructions disagree. Combine both contributions using the policy, then review and integrate the result into main.

Starter: https://github.com/kalviumcommunity/endsem-equipment-booking

Your assigned repository contains main, contributor/access and contributor/returns. Work only in your assigned copy. Do not edit POLICY.md or README.md.

## Requirements

The cancellation notice must be at least 24 hours before the booking. Keep the guide's heading and all three sections in their original order. Preserve the access contributor's ID-check instruction and the returns contributor's damage-report instruction, each in its corresponding section. Do not retain either obsolete cancellation notice or conflict markers. POLICY.md states these same requirements.

## Task 1: Inspect both contributions

Inspect initial main status, available branches and commit history. Read policy and display booking-guide.txt from both contributor branches without changing them. Identify the conflicting instruction, required policy outcome and each independent addition.

Evidence: initial clean main, branches/history, policy, both proposed files and a short explanation of the disagreement and additions.

## Task 2: Prepare the integration

Create an integration branch from main. Merge contributor/access first. Inspect the merge result, history and clean working tree. Compare this intermediate guide with the requirements and identify what still needs changing or adding before integration is complete.

Evidence: branch creation, first merge, intermediate guide/history/status and remaining-work explanation.

## Task 3: Resolve and verify

Merge contributor/returns into the same integration branch. Capture the actual conflict message, status and conflicted file before editing. Resolve booking-guide.txt against the requirements while preserving both independent contributions. Stage and complete the merge. Check the final guide, absence of conflict markers, merge history and clean working tree. Explain why choosing one entire contributor version would be incomplete.

Evidence: genuine conflict, before/after file, completed merge with both parents visible in history, checks/status and explanation. Change only booking-guide.txt. Do not rewrite history.

## Task 4: Review and integrate

Push integration branch and open a PR from it into main in the same assigned repository. Use a clear title and describe the conflict, policy decision, preserved additions and checks actually performed. Capture open PR before merging. Leave one ordinary self-review comment confirming the requirements. Merge PR, pull main locally and verify final guide and clean state. Capture PR comment and merged state as well as local result.

Evidence: successful push, open PR with direction/description, actual self-review, merged PR and updated local main/content/status. A self-review is not independent approval.

## Submission

Submit one PDF containing solutions for all four tasks. Organise it into Task 1 to Task 4. Include the screenshots requested in each task, with a one- or two-sentence label explaining the result and answering any requested short question. Multiple readable screenshots per task are allowed. Do not include credentials.

