# Agent Skills: Knowledge Catalog (formerly known as Dataplex)

> [!NOTE]
> Currently in beta (pre-v1.0), and may see breaking changes until the first stable release (v1.0).

This repository packages [MCP Toolbox](https://github.com/googleapis/mcp-toolbox)'s prebuilt `dataplex` server as a plugin/extension to interact with [Knowledge Catalog](https://cloud.google.com/dataplex/docs) (formerly known as Dataplex) instances. It can be used with various AI agents, including [Antigravity](https://antigravity.google/), [Claude Code](https://claude.com/product/claude-code) and [Codex](https://developers.openai.com/codex), to discover, manage, monitor, and govern data and AI artifacts across your data platform using natural language prompts.

> [!IMPORTANT]
> **We Want Your Feedback!**
> Please share your thoughts with us by filling out our feedback [form][form]. 
> Your input is invaluable and helps us improve the project for everyone.

[form]: https://docs.google.com/forms/d/e/1FAIpQLSfEGmLR46iipyNTgwTmIDJqzkAwDPXxbocpXpUbHXydiN1RTw/viewform?usp=pp_url&entry.157487=dataplex

## Table of Contents

- [Why Use Knowledge Catalog?](#why-use-knowledge-catalog)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Configuration](#configuration)
  - [Installation & Usage](#installation--usage)
    - [Antigravity](#antigravity)
    - [Claude Code](#claude-code)
    - [Codex](#codex)
- [Installing via a compatible Agent Plugins client](#installing-via-a-compatible-agent-plugins-client)
- [Usage Examples](#usage-examples)
- [Available Tools](#available-tools)
- [Generating Skills Instead](#generating-skills-instead)
- [Additional Agent Skills](#additional-agent-skills)
- [Troubleshooting](#troubleshooting)

## Why Use Knowledge Catalog?

* **Natural Language Management:** Stop wrestling with complex commands. Explore schemas and query data by describing what you want in plain English.
* **Seamless Workflow:** Integrates seamlessly into your AI agent's environment. No need to constantly switch contexts for common database tasks.
* **Code Generation:** Accelerate development by asking your agent to generate data classes and other code snippets based on your table schemas.

## Prerequisites

Before you begin, ensure you have the following:

- One of these AI agents installed
  - Antigravity
     - [Antigravity CLI](https://github.com/google-gemini/gemini-cli) version **v1.6.0** or higher
     - [Antigravity 2.0](https://antigravity.google/product/antigravity-2) version **v2.0.0** or higher.
  - [Claude Code](https://claude.com/product/claude-code) version **v2.1.94** or higher.
  - [Codex](https://developers.openai.com/codex) **v0.117.0** or higher.
- [Node.js](https://nodejs.org/) — the MCP server runs via `npx`.
- A Google Cloud project with the **Dataplex API** enabled.
- Ensure [Application Default Credentials](https://cloud.google.com/docs/authentication/gcloud) are available in your environment.
- IAM Permissions:
  * Dataplex Data Reader (`roles/dataplex.dataReader`): For reading data from the underlying assets (e.g., to run analytics queries).
  * Service Usage Consumer (`roles/serviceusage.serviceUsageConsumer`)

## Getting Started

### Configuration

Please keep these env vars handy during the installation process:

*   `DATAPLEX_PROJECT`: The GCP project ID.

### Installation & Usage

To start interacting with your database, install the extension for your preferred AI agent, then launch the agent and use natural language to ask questions or perform tasks.

For the latest version, check the [releases page][releases].

[releases]: https://github.com/gemini-cli-extensions/knowledge-catalog/releases

<!-- {x-release-please-start-version} -->

<details open>
<summary id="antigravity">Antigravity</summary>

You can use either of these two agents for Antigravity:
- [Antigravity CLI](https://github.com/google-gemini/gemini-cli) version **v0.5.4** or higher
- [Antigravity 2.0](https://antigravity.google/product/antigravity-2) version **v0.5.4** or higher.

<blockquote>
💡 <strong>Tip — Migrating from Gemini CLI?</strong><br>
If you previously installed this extension with <code>gemini extensions install</code>, you can convert it to an Antigravity plugin instead of reinstalling from scratch:
<ul>
  <li><strong>On first launch of Antigravity CLI</strong>, accept the Migration Options prompt to automatically convert your installed Gemini CLI extensions to Antigravity plugins.</li>
  <li><strong>Or, from your terminal</strong>, run:
    <pre><code class="language-bash">agy plugin import gemini</code></pre>
  </li>
</ul>
See <a href="https://antigravity.google/docs/gcli-migration">Migrating from Gemini CLI</a> for details on plugins, context files (<code>GEMINI.md</code> / <code>AGENTS.md</code>), and MCP server config differences.
</blockquote>

#### Antigravity 2.0 (IDE)

**1. Install the plugin:**

Install the plugin directly from the remote GitHub repository:

```bash
agy plugin install https://github.com/gemini-cli-extensions/knowledge-catalog
```

**2. Set env vars:**
Set your environment vars as described in the [configuration section](#configuration).

_(Tip: You can verify the MCP server is active by running the `/mcp` command in your active session.)_

#### Antigravity CLI

You can install plugins directly from a remote GitHub repository.

**1. Install the plugin:**

```bash
agy plugin install https://github.com/gemini-cli-extensions/knowledge-catalog
```

**2. Set env vars:**
Set your environment vars as described in the [configuration section](#configuration).

</details>

<details>
<summary id="claude-code">Claude Code</summary>

**1. Set env vars:**
In your terminal, set your environment vars as described in the [configuration section](#configuration).

**2. Start the agent:**

```bash
claude
```

**3. Install the plugin:**

```bash
/plugin install knowledge-catalog@claude-plugins-official
```

_(Tip: Run `/plugin list` inside Claude Code to verify the plugin is active, or `/reload-plugins` if you just installed it.)
</details>

<details>
<summary id="codex">Codex</summary>

**1. Install marketplace:**

```bash
codex plugin marketplace add GoogleCloudPlatform/data-agent-kit
```

**2. Install the plugin:**

```bash
codex plugin add knowledge-catalog@data-agent-kit
```

**3. Set env vars:**
Enter your environment vars as described in the [configuration section](#configuration).

**4. (Optional) Update the marketplace:**
```sh
codex plugin marketplace upgrade data-agent-kit
```

</details>

## Installing via a compatible Agent Plugins client
## Installing via a compatible Agent Plugins client

This repository is a valid [Agent Plugins](https://github.com/agentplugins/agent-plugins-spec) (v1) plugin. Any [Agent Plugins–compatible client](https://agent-plugins.org/compatible-clients) can install it directly using its own built-in plugin command — no extra tooling required — by pointing at this repository:

```
https://github.com/gemini-cli-extensions/knowledge-catalog
```

Beyond harnesses covered by the native install above, compatible clients include VS Code, Cursor, GitHub Copilot, and Kiro. See your agent's documentation for its exact install command.

**Set env vars:**
Set your environment vars as described in the [configuration section](#configuration).

<!-- {x-release-please-end} -->

## Usage Examples

Interact with Knowledge Catalog using natural language:

* **Explore Catalog and Metadata:**
  * "Find all catalog entries related to 'customer orders'."
  * "Which columns look similar across marketing and sales datasets?"
  * "Show me the description and owner for the 'customer_pii' entry."

* **Perform Ad-hoc Analysis:**
  * "Calculate the total 'customer orders' this month."

## Available Tools

The tools come from MCP Toolbox's prebuilt `dataplex` server, grouped into toolsets:



For the full, up-to-date list, see the [`dataplex` prebuilt config](https://github.com/googleapis/mcp-toolbox/blob/main/internal/prebuiltconfigs/tools/dataplex.yaml)
in the MCP Toolbox repository.

## Generating Skills Instead

The tool-backed skills this plugin used to ship were generated from the same prebuilt
toolsets. If your agent lacks deferred tool loading, or you prefer skills, regenerate
them with the script in this repository:

```bash
VERSION=<toolbox version> ./.github/scripts/generate_skills.sh
```

Use the toolbox version pinned in [`mcp.json`](./mcp.json). A single toolset, without
the script:

```bash
npx @toolbox-sdk/server@<toolbox version> --prebuilt dataplex skills-generate \
  --name "<skill name>" \
  --toolset "<toolset>" \
  --description "<what it is for>"
```

The generated scripts call the toolbox through `npx`, so no binary download is needed.
See [Generate Agent Skills](https://github.com/googleapis/mcp-toolbox#generate-agent-skills)
in the MCP Toolbox repository.

## Additional Agent Skills

Find additional skills to support your entire software development lifecycle at [github.com/gemini-cli-extensions](https://github.com/gemini-cli-extensions).

## Troubleshooting

Use the debug mode of your agent (e.g., `gemini --debug`) to enable debugging.

Common issues:

* "failed to find default credentials: google: could not find default credentials.": Ensure [Application Default Credentials](https://cloud.google.com/docs/authentication/gcloud) are available in your environment. See [Set up Application Default Credentials](https://cloud.google.com/docs/authentication/external/set-up-adc) for more information.
* "✖ Error during discovery for server: MCP error -32000: Connection closed": The database connection has not been established. Ensure your configuration is set via environment variables.
* "✖ MCP ERROR: Error: spawn .../toolbox ENOENT": The Toolbox binary did not download correctly. Ensure you are using the latest version of your agent.
* "cannot execute binary file": The Toolbox binary did not download correctly. Ensure the correct binary for your OS/Architecture has been downloaded. See [Installing the server](https://mcp-toolbox.dev/documentation/introduction/#install-toolbox) for more information.
