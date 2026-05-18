# project-to-resume

A Claude Code skill that transforms completed projects into resume-ready bullet points.

## What it does

When you finish a project and want to add it to your resume, this skill:

1. Asks about your target job position
2. Analyzes the project from your conversation context
3. Outputs two versions with different angles (product-focused vs technical-focused)
4. Includes reasoning for each writing approach

## Usage

Just say something like:
- "写简历"
- "总结这个项目放到简历里"
- "这个项目不错，想写进简历"

The skill will automatically trigger and guide you through the process.

## Output format

Two versions in copyable code blocks:

- **Version A**: Product thinking focus — emphasizes user insight, feature prioritization, product decisions
- **Version B**: Technical implementation focus — emphasizes architecture, engineering, technical stack

Each version includes a brief explanation of the writing approach.

## Customization

Edit `SKILL.md` to adjust:
- Output format and structure
- Writing principles and style
- Example outputs
