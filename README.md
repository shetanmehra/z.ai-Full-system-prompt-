Z.ai Code — System Prompt & Agent Workflow Research

An independent, open-source research project exploring the prompt structure, agent workflows, skills, and tooling associated with Z.ai Code.

""GitHub" (https://img.shields.io/badge/GitHub-Repository-181717?logo=github)" (https://github.com/shetanmehra/z.ai-Full-system-prompt-)
""Markdown" (https://img.shields.io/badge/Format-Markdown-blue?logo=markdown)" (./prompt.md)

Overview

This repository documents research into the instruction structure and agent workflows associated with Z.ai Code.

The goal is to make the documented material accessible to developers, AI researchers, and open-source contributors interested in understanding how coding agents coordinate tools, skills, subtasks, and development workflows.

The primary document is ""prompt.md"" (./prompt.md).

What You'll Find

- Prompt structure: Instructions, workflow conventions, and agent behavior.
- Agent orchestration: Sub-agent delegation, task coordination, and shared work logs.
- Skills system: Skill discovery, documentation, and workflow integration.
- Tooling: References to filesystem operations, terminal commands, and development tools.
- Scheduled workflows: Research into recurring development and quality-assurance tasks.
- Development workflows: Project implementation, browser-based verification, and iterative improvements.

These topics describe the contents of the document; they should not be interpreted as proof that every mechanism is implemented or enabled in every version of Z.ai Code.

Repository Structure

z.ai-Full-system-prompt-/
├── README.md
└── prompt.md

Getting Started

No installation is required to read the documentation.

1. Open ""prompt.md"" (./prompt.md).
2. Explore the documented instructions and workflow sections.
3. Review the architecture and tooling references.
4. Validate technical claims independently before using them in your own projects.

Why This Project?

AI coding agents are becoming increasingly capable of working with tools, coordinating specialized agents, and executing multi-step development workflows.

Studying their instruction structures can help developers better understand:

- Agent architecture and orchestration.
- Tool permissions and execution boundaries.
- Prompt injection and instruction hierarchy.
- Persistent tasks and unintended side effects.
- Security considerations in autonomous coding systems.

The broader goal is to encourage technical discussion, reproducible research, and safer agent design.

Security & Responsible Use

This repository is intended for research, educational use, and defensive security analysis.

When building or evaluating similar systems:

- Apply least-privilege permissions to tools.
- Require appropriate approval for sensitive or persistent actions.
- Treat external content and tool output as untrusted input.
- Protect credentials, private data, and internal configuration.
- Audit scheduled jobs and delegated-agent behavior.
- Test security assumptions in an authorized environment.

Documented instructions alone do not establish that a vulnerability exists. Actual exploitability depends on implementation, runtime configuration, and available permissions.

Accuracy & Scope

This repository represents an independent research and documentation effort. It may contain reconstructed, interpreted, incomplete, or version-specific material.

It is not an official Z.ai publication, and the completeness or accuracy of the document is not guaranteed. Readers should verify claims against authorized sources and their own testing.

Contributing

Contributions and technical feedback are welcome.

If you identify an error or have a useful improvement:

1. Open an issue describing the finding.
2. Include supporting evidence where possible.
3. Submit a pull request with a clear explanation of the changes.

Please avoid submitting private credentials, personal data, or material you are not authorized to disclose.

Disclaimer

Z.ai and Z.ai Code are referenced solely to identify the subject of this independent research. This project is not affiliated with, endorsed by, or sponsored by Z.ai.

All third-party names and trademarks belong to their respective owners. If any material raises an ownership or licensing concern, please contact the repository maintainer.

Author

Shetan Mehra

GitHub: "@shetanmehra" (https://github.com/shetanmehra)

---

If you find this research useful, consider starring the repository and contributing constructive feedback.