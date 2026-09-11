# Thread CRM Documentation

Welcome to the official documentation repository for **Thread CRM**.

This project contains the product, user, administrator, developer, API, and integration documentation for Thread CRM. The documentation is built and maintained using Mintlify.

## Overview

Thread CRM is a modern, multi-tenant sales and marketing CRM designed to help teams manage their complete go-to-market workflow from a single platform.

The platform brings together capabilities such as:

* Lead and contact management
* Company and account management
* Deal and pipeline management
* Sales activities and tasks
* Email and outreach automation
* Calling and communication
* Workflow automation
* Data enrichment
* AI-powered assistance and agents
* Custom objects and fields
* Integrations
* Analytics and reporting
* Workspace and user management

## Documentation Structure

The documentation is organized into the following major sections:

```text
docs/
├── index.mdx
├── introduction.mdx
├── quickstart.mdx
├── changelog.mdx
│
├── records/
│   ├── people.mdx
│   ├── companies.mdx
│   ├── leads.mdx
│   ├── deals.mdx
│   ├── tasks.mdx
│   └── notes.mdx
│
├── engage/
│   ├── email-sequences.mdx
│   ├── email-templates.mdx
│   ├── call-logs.mdx
│   └── forms-iq.mdx
│
├── settings/
│   ├── workspace.mdx
│   ├── members-roles.mdx
│   ├── custom-fields.mdx
│   ├── email-setup.mdx
│   └── api-keys.mdx
│
├── images/
│   ├── logo.png
│   ├── logo-light.png
│   ├── logo-dark.png
│   ├── background.avif
│   ├── platform/
│   ├── records/
│   └── releases/
│
├── docs.json
├── openapi.json
└── style.css
```

> The exact structure may evolve as Thread CRM continues to grow.

## Local Development

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm, pnpm, or yarn
* Mintlify CLI

### Install Mintlify CLI

```bash
npm i -g mintlify
```

### Run the Documentation Locally

From the root directory of the documentation project:

```bash
mintlify dev
```

The documentation will be available locally at:

```text
http://localhost:3000
```

## Creating Documentation Pages

Documentation pages are typically written in MDX.

Example:

```mdx
---
title: Create a Lead
description: Learn how to create and manage leads in Thread CRM.
---

# Create a Lead

Leads represent potential customers or business opportunities.

## Create a new lead

1. Navigate to **Leads**.
2. Click **Create Lead**.
3. Enter the required information.
4. Click **Save**.

## Next Steps

- Convert the lead into a contact.
- Add the lead to a workflow.
- Enrich the lead with additional data.
```

## Writing Guidelines

When contributing documentation:

* Keep content clear and concise.
* Use task-oriented headings.
* Explain concepts before implementation details.
* Use examples wherever possible.
* Keep terminology consistent across the documentation.
* Prefer real Thread CRM workflows over generic examples.
* Use code blocks for technical examples.
* Keep screenshots and visuals relevant and up to date.
* Link related documentation pages where helpful.

## Documentation Categories

### User Documentation

Documentation for end users covering:

* Getting started
* CRM features
* Lead and contact management
* Deals and pipelines
* Tasks and activities
* Email and outreach
* Workflows
* Reporting

### Administrator Documentation

Documentation for workspace and system administrators covering:

* Workspace configuration
* User management
* Roles and permissions
* Custom fields and objects
* Integrations
* Subscription and billing settings

### Developer Documentation

Technical documentation covering:

* Thread CRM architecture
* APIs
* Authentication
* Webhooks
* Integrations
* Custom object development
* Extension points

### AI Documentation

Documentation covering AI-powered capabilities such as:

* Thread CRM Copilot
* AI Agents
* Lead Qualification Agent
* Research and enrichment
* AI-assisted workflows

## AI and LLM Support

This documentation project includes:

* `llms.txt` — A concise overview of Thread CRM documentation for AI systems.
* `llms-full.txt` — A comprehensive documentation source optimized for AI retrieval and reasoning.

These files help AI assistants and agents understand Thread CRM concepts, capabilities, and workflows.

## Before Submitting Changes

Before submitting documentation changes:

* [ ] Verify that all links work correctly.
* [ ] Check spelling and grammar.
* [ ] Confirm technical information is accurate.
* [ ] Ensure examples reflect the current product behavior.
* [ ] Verify navigation in `docs.json`.
* [ ] Run the documentation locally.
* [ ] Check MDX rendering and formatting.
* [ ] Remove outdated references.
* [ ] Add related links where useful.

## Contributing

When adding a new feature to Thread CRM, documentation should ideally include:

1. **Overview** — What problem does the feature solve?
2. **Concepts** — Key terminology and architecture.
3. **Getting Started** — How users can begin using the feature.
4. **Configuration** — Required setup and settings.
5. **Usage** — Step-by-step workflows.
6. **Examples** — Common real-world use cases.
7. **API Reference** — If applicable.
8. **Troubleshooting** — Known issues and solutions.
9. **Related Resources** — Links to relevant documentation.

## Versioning

Documentation should reflect the currently supported version of Thread CRM.

For significant releases:

* Document new features.
* Update changed workflows.
* Deprecate outdated functionality.
* Add migration guidance when required.
* Update release notes.

## Project Goals

The goal of this documentation is to provide a single, reliable source of knowledge for everyone using or building with Thread CRM.

We aim to make the documentation:

* **Clear** — Easy to understand.
* **Accurate** — Aligned with the product.
* **Practical** — Focused on real workflows.
* **Discoverable** — Easy to navigate and search.
* **Developer-friendly** — Useful for technical integrations.
* **AI-ready** — Structured for modern AI assistants and agents.

---

**Thread CRM Documentation**
Built with Mintlify.
