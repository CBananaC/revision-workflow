# Revision — project rules

## Purpose and scope

- Project root: `/Users/creamybanana/Downloads/Revision`
- Type: `hybrid`
- Purpose: A source-preserving revision workflow spanning ChatGPT on iPhone and Mac, Mac Codex, OpenCode and other AI, and future iPhone webapps. It transforms suitable class materials into an LLM Wiki when useful, keeps original PDFs authoritative, supports visual retrieval when needed, and records lecture notes, question-and-answer mistakes, unknown vocabulary, spaced revision, assessments, and schedules.
- Intended users: The learner using ChatGPT on iPhone and Mac, Mac Codex, OpenCode or other AI agents, and future course and vocabulary webapps.
- Main outcome: A repeatable workflow that ingests course materials, chooses original-PDF or LLM-Wiki processing by source type, supports part-by-part AI teaching and questioning, preserves precise generated notes and mistake/vocabulary records in Markdown, and feeds private study data into course and IELTS-style practice webapps.

Preserve source material and user-owned edits. Do not expand the scope without discussing it first.

## Required project files

- `PROJECT_DESCRIPTION.md` is the stable project brief.
- `PROJECT_LOG.md` is append-only and records concise action summaries, not full prompts or secrets.
- Update this `AGENTS.md` when project rules, source-of-truth paths, commands, or boundaries change.

## Git and remote boundaries

- Commit after every individual file write when Git is available; stage only the intended file and verify the commit hash.
- GitHub visibility decision: `public`. Ask before creating or connecting a remote repository.
- Google Drive sharing decision: `restricted`. Ask before creating a folder, changing permissions, or uploading files.
- Do not push, publish, upload, or send external messages without explicit approval.

## Safety and validation

- Never print, store, commit, or upload passwords, tokens, API keys, cookies, private keys, credential files, or one-time codes.
- Read before writing; preserve unrelated changes; avoid destructive commands.
- Validate the actual requested surface and record evidence in `PROJECT_LOG.md`.
- Keep the local project folder as the source copy unless the user explicitly requests a move.
