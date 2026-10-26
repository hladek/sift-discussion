# sift-discussion
ChatGPT Skill that helps with assessment of facts in political discussions, based on the SIFT method (Stop, Investigate the source, Find better coverage, Trace claims).

## Contents

- `skills/sift-discussion/SKILL.md` – the skill (instructions and output format)
- `skills/sift-discussion/references/manipulation-techniques.md` – reference list of rhetorical/manipulation techniques

## Use in ChatGPT web interface

1. Zip the skill folder: `cd skills && zip -r sift-discussion.zip sift-discussion`
2. In ChatGPT, open the skills settings and upload `sift-discussion.zip` (the folder must contain `SKILL.md` at its top level).
3. In a chat, paste a message or claim from a discussion and ask e.g. "Assess this claim" (or invoke the skill by name, `sift-discussion`).

If skills are unavailable in your plan, paste the body of `SKILL.md` into a Custom GPT's instructions or a chat as a prompt and upload the reference file as knowledge.
