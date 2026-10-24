### Copilot Instructions

Contains my copilot instruction file, for use in repos as a submodule.

### Use
- run this inside your main project repo: git submodule add https://github.com/your-username/my-copilot-rules.git .github/shared-copilot
- create link: 
-- linux: ln -s shared-copilot/.github/copilot-instructions.md .github/copilot-instructions.md
-- win/powershell: New-Item -ItemType SymbolicLink -Path ".github\copilot-instructions.md" -Target "shared-copilot\.github\copilot-instructions.md"
