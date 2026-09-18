This is a Salesforce DX project.

Rules:
- Use modern `sf` CLI commands.
- Before running org commands, verify file paths exist.
- Look for `sfdx-project.json` and `config/project-scratch-def.json` first.
- If scratch org definition file is missing, create a minimal valid one.
- Never assume Dev Hub alias exists; verify with org listing first.
- Keep changes minimal and show exact commands before suggesting destructive actions.
- After file changes, show git status and propose a commit message.
