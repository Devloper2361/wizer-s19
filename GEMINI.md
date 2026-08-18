# WIZER S19 — Gemini Development Rules

## Project

WIZER is our implementation of SOA Ideathon 2026 problem statement S19.

The project must remain aligned with the official S19 problem statement.

## General Rules

1. Read this file before making changes.
2. Read ARCHITECTURE.md before changing architecture.
3. Read API_CONTRACT.md before implementing or consuming APIs.
4. Do not redesign the project without approval.
5. Do not modify another member's module unnecessarily.
6. Do not delete working functionality.
7. Do not introduce unnecessary dependencies.
8. Do not expose API keys, passwords, tokens or secrets.
9. Never commit .env files.
10. Keep changes focused on the assigned task.
11. Preserve existing functionality.
12. Run tests/build checks after making changes.
13. Explain significant architectural changes before implementing them.
14. Do not fabricate data or claim unsupported accuracy.
15. Privacy must be preserved.
16. Do not implement continuous identifiable user tracking.
17. All location-related functionality must follow the project's privacy design.
18. If requirements conflict, stop and ask for clarification.

## AI Coding Rule

Do not blindly generate large amounts of code.

First inspect:
- repository structure
- existing implementation
- architecture
- APIs
- relevant module

Then implement the smallest correct change.

After implementation:
- test it
- report modified files
- report errors
- explain any new dependency