# Management Plugins Marketplace

A collection of Claude Code plugins for project management and productivity.

## Available Plugins

### 1. Jira AI Connector (`jira-ai-connector`)
An advanced assistant for Jira. It helps you manage tasks, brainstorm ideas, and update issues directly from Claude using the `jira-ai` CLI tool.

**Skills:**
- `work-with-jira`: Brainstorm, summarize, and update Jira tasks.

---

## Installation

### For Claude Code
#### Step 1: Add the Marketplace
Add this marketplace to your Claude instance:
```bash
claude plugin marketplace add festoinc/management-plugins
```

#### Step 2: Install the Plugin
```bash
claude plugin install jira-ai-connector@management-plugins
```

### For Gemini CLI
#### Step 1: Add the Extension
Add this extension to your Gemini CLI:
```bash
gemini extension install https://github.com/festoinc/management-plugins
```

## Prerequisites
Both plugins require the `jira-ai` CLI tool:
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

