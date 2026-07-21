# Image-Prompts Repository Rules

These rules are mandatory for all work in this repository.

## Non-Negotiable Rules

- Never delete image files.
- Never archive image files.
- Always append new files to the repository when adding new prompt sets, reference material, or image-related assets.
- Never allow duplicate prompts in any prompt file.
- Before adding or committing prompt text, check the target file and any other prompt files for exact duplicate prompt lines.
- Keep prompt files one prompt per line unless Nic explicitly requests another format.
- New prompt batches should contain 500 prompts by default unless Nic explicitly requests another count.
- Do not include aspect-ratio parameters such as `--ar`; Nic sets aspect ratio manually.
- Nic is a solo developer working on private repositories. Commit and push changes directly to `main`; do not create pull requests or release workflows unless Nic explicitly requests them.

## Change Records

- Update `CHANGELOG.md` for every committed change.
- Explain whether prompts were added, rules changed, or metadata/docs changed.
