# Security Policy

## Reporting a vulnerability

Please do not report security vulnerabilities through public issues, discussions, or pull requests.

Report them privately through GitHub's private vulnerability reporting:

1. Go to the [drizza-dev/drizza](https://github.com/drizza-dev/drizza) repository.
2. Open the **Security** tab.
3. Click **Report a vulnerability** and fill in the form.

Please include:

- A description of the issue and its impact.
- Steps to reproduce, or a proof of concept.
- The drizza version (or commit) and your environment (OS, Node.js version).
- Any suggested fix or mitigation, if you have one.

## Scope

This policy covers the open source drizza project: the local server and dashboard that run on your machine via `npx drizza`, including the MCP interface, the local HTTP server, and local data storage.

Examples of what we want to hear about:

- Ways for another site, process, or network host to reach or control the local server.
- Ways for credentials or briefing data to leave the user's machine unintentionally.
- Injection or code execution through data pulled from GitHub, Slack, or an agent.

Hosted services operated by drizza are not covered by this policy.

## What to expect

- We will acknowledge your report as soon as we can.
- We will investigate, keep you updated on progress, and may ask follow-up questions.
- Once a fix is available, we will publish an advisory and credit you, unless you prefer to remain anonymous.

drizza is maintained by a small team, so response times vary. We do not commit to a fixed timeline, but every report is read and taken seriously.

Please give us a reasonable amount of time to release a fix before disclosing the issue publicly.
