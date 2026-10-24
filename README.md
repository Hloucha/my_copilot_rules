# my_copilot_rules

Contains my copilot instruction file, use in repos as a submodule:

# Use Run this inside your main project repo:
git submodule add https://github.com/your-username/my-copilot-rules.git .github/shared-copilot

# Linux
ln -s shared-copilot/.github/copilot-instructions.md .github/copilot-instructions.md

# Win Powershell
New-Item -ItemType SymbolicLink -Path ".github\copilot-instructions.md" -Target "shared-copilot\.github\copilot-instructions.md"
