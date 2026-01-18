# Management Plugins Marketplace

A collection of Claude Code plugins for project management and productivity.

## Available Plugins

### 1. Jira AI Connector (`jira-ai-connector`)
An advanced assistant for Jira. It helps you manage tasks, brainstorm ideas, and update issues directly from Claude using the `jira-ai` CLI tool.

**Skills:**
- `work-with-jira`: Brainstorm, summarize, and update Jira tasks.

---

## Installation

### Step 1: Add the Marketplace
Add this marketplace to your Claude instance:

```bash
claude plugin marketplace add festoinc/management-plugins
```

### Step 2: Install the Plugin
Install the Jira AI Connector:

```bash
claude plugin install jira-ai-connector@management-plugins
```

### Step 3: Prerequisites
The Jira AI Connector requires the `jira-ai` CLI tool. If you don't have it, install and configure it:

```bash
npm install -g jira-ai
jira-ai auth login
```

---

## Usage

Once installed, you can trigger the Jira assistant using the slash command:

```bash
/work-with-jira
```

Or simply ask Claude:
*"Use the jira-manager plugin to summarize task PROJ-123"*

---

## Development

To validate the marketplace locally:
```bash
claude plugin validate .
```
