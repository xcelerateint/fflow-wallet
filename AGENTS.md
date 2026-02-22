# AGENTS.md — Instructions for AI Agents

## Repository: xcelerateint/fflow-wallet

### Stack
C++ blockchain wallet. Testing: make check. CRITICAL: handles private keys and transactions. All changes require human review.

### Branching
- Development branch: `master`
- AI implementation branches: `ai/issue-{N}`
- All PRs target: `master`

### Risk Tier: high
- **Human approval required** for all merges
- Extra scrutiny on security-sensitive changes
- No auto-merge under any circumstances

### Conventions
- Follow existing code style and patterns in this repository
- Do not introduce new dependencies without explicit plan approval
- Keep changes minimal and focused on the plan's `files_allowed` list
- Run all tests from `tests_required` before creating a PR

### File Structure
See the repository file tree for current layout. Key directories:
- `src/` — C++ source
- `test/` — Test files
