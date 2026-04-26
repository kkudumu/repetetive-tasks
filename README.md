# repetetive-tasks

IT ops skills and automation playbooks for Claude Code.

---

## Skills

### `/it-ops` — IT Operations Assistant

Pulls your Freshservice and Jira tickets into a task list, drafts ticket replies, helps troubleshoot IT issues, and builds automations or scripts.

**What it does:**
- Syncs all open tickets assigned to you from Freshservice and Jira into a `TodoWrite` task list
- Drafts ticket replies in a professional, direct tone — saves each draft as a markdown file and shows it in chat before sending
- Walks through IT troubleshooting diagnostics step by step
- Writes complete PowerShell, Python, Bash, or Freshservice workflow automations on request

**Invoke it:** type `/it-ops` in Claude Code

---

## Installation

### Prerequisites

- [Claude Code](https://claude.ai/code) installed
- Freshservice MCP server configured
- Jira MCP server configured

### Install the skill

1. Download [`skills/it-ops.skill`](skills/it-ops.skill) from this repo

2. In Claude Code, run:
   ```
   /install-skill path/to/it-ops.skill
   ```

3. Verify it's available:
   ```
   /it-ops
   ```

That's it. The skill is ready to use.

---

## Usage examples

```
/it-ops
> pull my tickets
```

```
/it-ops
> write a reply to ticket #5821 — user says their laptop was wiped during the OS refresh
```

```
/it-ops
> build a powershell script that checks if users in this CSV have MFA enabled in Entra ID
```

```
/it-ops
> our freshservice onboarding workflow stopped triggering — help me troubleshoot
```
