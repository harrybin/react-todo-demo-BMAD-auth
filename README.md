# BMAD requirements and testing demo

This repository accompanies the **“KI-gestützte Anforderungs- und Testfallentwicklung”** presentation:
[view the slides](https://presentations.harrybin.de/bmad-anforderungen-tests/).

This is the repository for the presentation demo, **not a live demo**. The recorded
GitHub Copilot chat shows the BMAD-assisted requirements and test-planning process.
It took a little over two hours and covered requirements, planning, architecture,
and testing; application source-code creation was not part of that recorded process.

## Chat history and highlights

The exported GitHub Copilot chats are Markdown files in
[bmad-atdd-chat-histroy](bmad-atdd-chat-histroy/). The folder
[index](bmad-atdd-chat-histroy/index.md) links to every export. Highlights from
the recorded workflow:

1. [Starting the BMAD product-manager workflow](bmad-atdd-chat-histroy/2026-05-02_230358_bmad-agent-pm-command_2a583496.md)
2. [Expanding the enterprise authentication requirements](bmad-atdd-chat-histroy/2026-05-02_232334_enterprise-authentication-system-expansion_f1bf89cb.md)
3. [Generating project context](bmad-atdd-chat-histroy/2026-05-03_002044_bmad-project-context-generation_cc6130d7.md)
4. [Creating epics and stories](bmad-atdd-chat-histroy/2026-05-03_002503_create-epics-and-stories_7cc2cdef.md)
5. [Using the BMAD Test Architect (TEA)](bmad-atdd-chat-histroy/2026-05-03_004910_bmad-tea-command-usage_544388d4.md)
6. [Updating the architecture](bmad-atdd-chat-histroy/2026-05-03_004930_bmad-create-architecture-update_6f1a84be.md)
7. [Continuing the Test Architect workflow](bmad-atdd-chat-histroy/2026-05-03_005715_bmad-tea-command-usage_772f6263.md)
8. [Creating test traceability](bmad-atdd-chat-histroy/2026-05-03_011505_bmad-testarch-trace_7680b9f8.md)

## Install BMAD

For a new project, install the stable BMAD Method from the VS Code integrated
terminal. The installer requires Node.js 20.12 or newer, Python 3.10 or newer,
and `uv`:

```bash
npx bmad-method install
```

Follow the installer's prompts to select the project modules and configure your
AI coding tool. For details, see the [presentation](https://presentations.harrybin.de/bmad-anforderungen-tests/)
and the [BMAD installation guide](https://docs.bmad-method.org/start/build-your-first-change/).

## Install the BMAD Viewer for VS Code

Install **BMAD Viewer** (`rdudiver.bmad-viewer-vscode`) from the VS Code
Extensions view by searching for its extension ID, or run:

```bash
code --install-extension rdudiver.bmad-viewer-vscode
```

The extension is also listed in this workspace's recommended extensions.

## Run the app

To run this repository's app locally, install [Node.js](https://nodejs.org/) and
then run:

```bash
npm install
npm run dev
```

For available project commands, see the [Contributing guide](CONTRIBUTING.md).

## Contributing

Contributions are welcome. Please see the [Contributor Guide](CONTRIBUTING.md)
and [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the [LICENSE](LICENSE).
