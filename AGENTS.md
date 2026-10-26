# Skill publishing workflow

## Standing user instruction

As requested on 2026-10-26, automatically publish each new or updated user-created skill to `bym6dn6zv5-gif/skills` on GitHub when completing the work. This is ongoing authorization; do not ask the user to repeat the upload request for every skill. Follow any later task-specific instruction that changes this default.

## Complete each skill delivery

1. Create or update the skill in the user's managed Skills workspace, validate it, and complete the normal managed save.
2. Read the destination repository's current default branch, instructions, and file tree through the authorized GitHub connection.
3. Use the `name` in SKILL.md as the GitHub folder, for example `academic/`, `living/`, or `poetic/`. Managed workspace folders may use stable IDs; do not copy those IDs into the GitHub layout.
4. Include SKILL.md, agents metadata, referenced guides, scripts, and required assets. Publish reusable skill sources; keep private conversations, personal records, temporary test outputs, and credentials out of the repository.
5. Add or update only the intended skill files. Preserve unrelated repository content. Use an atomic commit with the current branch head as its parent and a non-forced ref update with an expected-head check; re-read if the branch moved.
6. Verify the published files against the source. Report completion with the GitHub folder link, or clearly report an actual save or upload failure while preserving the source.

Do not treat a local commit, a ZIP package, or a proposed upload as a successful GitHub publication. Respect any access requirement actually returned by the connected tools.
