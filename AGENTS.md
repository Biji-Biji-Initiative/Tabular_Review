# AGENTS.md

## Repository Overview
Fork of [Tabular_Review](https://github.com/Kevin-Tucuxi/Tabular_Review) - AI-powered legal document review tool with Biji-Biji customizations.

## Upstream Sync
- Upstream: https://github.com/Kevin-Tucuxi/Tabular_Review
- Sync frequency: As needed
- Last sync: 2025-11-23

## Custom Modifications
- AI prompt customizations
- Document processing pipeline adjustments
- Integration with internal systems

## Core Commands
- Install: `npm install` or `pnpm install`
- Dev: `npm run dev`
- Test: `npm test`
- Build: `npm run build`
- Process document: `npm run process -- {file-path}`

## AI Configuration
- Model: Configure via `AI_MODEL` environment variable
- Prompts: Customize in `prompts/` directory
- Output: Check `output/` for processed results

## Validation Requirements
Before marking work as complete:
- Run: `npm run lint`
- Run: `npm test`
- Test document processing with sample files
- Verify AI output quality

## Boundaries
- ✅ Always: Validate document formats, log AI processing results, test prompts
- ⚠️ Ask First: Changes to AI prompts, document retention changes, new document types
- 🚫 Never: Store sensitive legal documents in repo, commit API keys, skip compliance checks

## Security Notes
- Never store real legal documents in the repository
- Use sample/test documents for development
- Ensure AI processing complies with data retention policies
- Sanitize logs of any sensitive information

---
Last updated: 2026-03-02
