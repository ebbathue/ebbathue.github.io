AABE course folder, version 2026-1
2026-10-26

## 2026-10-26, session 1, part 1: language models

What the student did: read session 1, gave the part 1 task prompt, and answered the three "You should be able to" questions. The answer to question 1 needed to be more specific: the student added that likely and plausible is not the same as correct.

Result of the small task (agent's answer):
- AGENTS.md asks the agent to:
  1. Start each session by writing the log's first line if missing, reading the log and asking which part.
  2. Follow folder-context whenever a file is created, moved, copied or saved.
  3. Ask before creating, changing or deleting a file, and never handle keys or passwords.
  4. Take the student through each task without doing it for them, then log the part.
  5. Write short plain sentences and never state an unchecked number.
- One thing a model gets wrong: it invents sources. Check by opening the source and finding the passage. Example from this run: AGENTS.md says to run prose_check.py, but the file does not exist in the folder, so it was not run.

## 2026-10-26, session 1, part 2: skills and folders

What the student did: read what folder-context contains and chose not to install it in the home folder, since it does not fit every project. It stays switched on in the course folder only. Gave the small task prompt and chose where the thesis should live. Answered the four questions. The answers to questions 3 and 4 needed to be more specific.

Result of the small task (agent's answer):
- Drew the course folder as a tree: .agents/skills/folder-context, .claude/skills/folder-context, AGENTS.md, CLAUDE.md, my-page/index.md, session-log.md, session1/ with three parts, skills/folder-context.
- Proposed a thesis folder, master-thesis/, with AGENTS.md, CLAUDE.md, README.md, raw-data/, literature/, work/, drafts/ and notes/ with dated names.
- folder-context started and asked where the thesis lives. Student's answer: iCloud Drive, a project of its own, at STUDIER/Master/master-thesis. The folder was not created.

## 2026-10-26, session 1, part 3: what an agent is

What the student did: watched the part 3 video and asked for the small task. Named the four parts of an agent after a correction: model, tools, loop, goal. Gave examples of model and tools. Loop and goal needed explanation with examples from the session. The student then described the loop as do, look, decide, using the failed part 1 write. The student stated the goal as getting through the three parts as the course files direct.

Result of the small task (agent's answer):
- Mapped ten steps of the session to the tool used, the result and the next decision. Tools: Bash (read, list, search, append), Edit (removed semicolons), AskUserQuestion (thesis storage).
- Example of the loop: the part 1 write returned an error, a read showed nothing was written, and the entry was written again.
- Goal: take the student through each part of session 1 and log each part after asking. It is checkable from the log entries. Whether the student can explain each result is a judgement the agent made.
