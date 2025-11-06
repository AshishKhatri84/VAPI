# VAPI

Assistant Demo Assistants: I-Bot & Maria

Overview

VAPI is a demo repository showcasing two assistant agents: I-Bot and Maria. It provides example implementations and resources for building, running, and experimenting with conversational assistants (chatbots) and related integration code.

Features

- Two demo assistants: I-Bot and Maria
- Example conversational flows and agent behavior
- Guidance for setup and local development

Repository structure (suggested)

- /ibot - Source and configuration for I-Bot assistant
- /maria - Source and configuration for Maria assistant
- /docs - Documentation and design notes
- /examples - Example scripts and usage samples
- README.md - This file

Getting started

Prerequisites

- Node.js (14+), Python 3.8+ or other runtime depending on assistant implementations
- Git

Install

1. Clone the repository:

   git clone https://github.com/AshishKhatri84/VAPI.git
   cd VAPI

2. Explore the folders for each assistant implementation (ibot and maria) and follow their local setup instructions. Each assistant may include a package.json, requirements.txt, or a README with details.

Usage

- To run an assistant locally, open the respective subfolder (for example `ibot`) and follow the run instructions there. Typical patterns:

  - For Node.js projects:

    npm install
    npm start

  - For Python projects:

    python -m venv .venv
    source .venv/bin/activate  # or .\venv\Scripts\activate on Windows
    pip install -r requirements.txt
    python main.py

Development

- Add new conversation flows and tests under the `examples` or assistant-specific folders.
- Keep configuration and secrets out of the repository. Use environment variables or a `.env` file (gitignored).
- Write unit and integration tests for critical logic.

Contributing

Contributions are welcome. Please open issues for bugs or feature requests and submit pull requests for enhancements. When contributing:

- Fork the repository
- Create a feature branch
- Add tests and documentation for your changes
- Open a pull request describing your changes

License

This repository currently has no license file. Add a LICENSE file if you want to set one (for example, MIT License).

Contact

Owner: @AshishKhatri84

If you want this README customized with project-specific run commands, architecture diagrams, or example code snippets for I-Bot and Maria, tell me what language/framework each assistant uses and I will update the README.