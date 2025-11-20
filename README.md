# Graphite-Phlow

<div align="center">

[![Status](https://img.shields.io/badge/Live_on_GitHub_Pages-2EA44F?style=for-the-badge&logo=github&logoColor=white)](https://dovvnloading.github.io/Graphite-Phlow/)

</div>

<div align="center">




<br />

![License](https://img.shields.io/badge/license-Apache_2.0-blue?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0.0-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![Tech](https://img.shields.io/badge/react-v19-black?style=flat-square)
![AI](https://img.shields.io/badge/Google-Gemini_3_Pro-blue?style=flat-square)

</div>

**Graphite-Phlow** is a next-generation, AI-powered coding IDE designed to bridge the gap between natural language concepts and executable code. It features a sophisticated **Agentic Build Mode** that simulates a full software development team—orchestrating a step-by-step, user-approved build process.

Built with React, Tailwind CSS, and the Google GenAI SDK, Graphite-Phlow leverages the latest Gemini models to provide deep reasoning, real-time web grounding, and semantic code search.


| | |
|---|---|
| <img src="https://github.com/user-attachments/assets/4037328b-5fb4-4af4-b8d1-800ca26c74b0" width="100%" /> | <img src="https://github.com/user-attachments/assets/a4da0a80-cd8a-45e9-a20d-80dd2a4a23bb" width="100%" /> |
| <img src="https://github.com/user-attachments/assets/85ac388e-0f9c-456c-9f78-fb710bfca851" width="100%" /> | <img src="https://github.com/user-attachments/assets/2913a456-8a12-42a5-8e38-1c4ea0ab112f" width="100%" /> |


---

## Table of Contents

1. [Key Features](#key-features)
2. [Agentic Build Mode](#agentic-build-mode)
3. [System Architecture](#system-architecture)
4. [Getting Started](#getting-started)
5. [Usage Guide](#usage-guide)
6. [Contributing](#contributing)
7. [License & Authors](#license--authors)

---

## Key Features

### Advanced AI Modes

*   **Quick Mode:** Powered by Gemini 2.5 Flash for lightning-fast edits and chat.
*   **Deep Think:** Leverages Gemini 2.5 Pro or Gemini 3 Pro with "thinking budgets" for complex reasoning and architectural decisions.
*   **Web Search:** Real-time grounding using Google Search to fetch up-to-date documentation and libraries.
*   **Code Search:** Semantic search across your entire active codebase to answer queries regarding variable definitions and file locations.

### Powerful Code Canvas

*   **Multi-Tab Editor:** Full-featured code editor with syntax highlighting for TypeScript, Python, HTML, CSS, and more.
*   **Smart Context:** Context-aware actions via right-click (Explain, Find Bugs, Generate Tests).
*   **Live Preview:** Instant, interactive preview for web projects with responsive testing tools (Mobile, Tablet, Desktop).
*   **Bug Repair Panel:** A dedicated workspace for analyzing errors and generating fixes without cluttering the main code view.

### Developer Experience

*   **GitHub Import:** Load public repositories directly into the workspace.
*   **Local Management:** Import local folders and save/load project states to browser storage.
*   **Floating Toolbar:** Context-aware tools appear adjacent to your cursor.
*   **Visual Diffing:** AI changes are presented as clear diffs, ensuring code integrity.

---

## Agentic Build Mode

Graphite-Phlow distinguishes itself with a structured, multi-agent workflow. You act as the stakeholder, approving each phase before execution.

| Agent Role | Responsibility |
| :--- | :--- |
| **Concept (Product Manager)** | Refines high-level prompts into a concrete product strategy, user flow, and core features. |
| **Architecture (System Architect)** | Designs the system, selecting the tech stack, defining data models, and structuring the file hierarchy. |
| **Plan (Tech Lead)** | Creates a detailed, step-by-step implementation roadmap. |
| **Execution (Developer)** | Writes the actual code based on the approved plan, maintaining context of the entire architecture. |

---

## System Architecture

Graphite-Phlow operates as a client-side Single Page Application (SPA).

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend Framework** | React 19, Vite | High-performance UI rendering. |
| **Styling** | Tailwind CSS | Dark/Light mode support with utility-first CSS. |
| **AI Layer** | Google GenAI SDK | Direct browser-to-API communication (no middleware). |
| **Editor** | react-simple-code-editor | Powered by PrismJS for syntax highlighting. |
| **State Management** | React Hooks & Context | Efficient local state handling. |

---

## Getting Started

### Prerequisites

*   **Node.js:** Version 18 or higher.
*   **Google Gemini API Key:** A paid tier may be required for advanced models (Gemini 3 Pro).

### Installation

1.  **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/graphite-phlow.git
    cd graphite-phlow
    ```

2.  **Install dependencies**

    ```bash
    npm install
    ```

3.  **Configure Environment**

    Create a `.env` file in the root directory and add your API key:

    ```env
    API_KEY=your_google_genai_api_key_here
    ```

4.  **Start the development server**

    ```bash
    npm run dev
    ```

---

## Usage Guide

### Enabling Agent Mode

1.  Toggle the **Agent Mode** switch located next to the "Send" button.
2.  Enter a high-level prompt (e.g., *"Build a Pomodoro timer with task tracking"*).
3.  The Agent Panel will open. Review the output from the **Product Manager Agent**.
4.  Click **Approve & Continue** to proceed through the Architect and Tech Lead phases.
5.  Upon final approval, the Developer Agent will generate and write code directly to your canvas.

### Using the Code Canvas

*   **Create File:** Click the **+** icon in the file tree or tab bar.
*   **Context Actions:** Select any text in the editor, then Right Click to access actions like "Refactor" or "Explain."
*   **Import Local Project:** Use the folder icon in the file explorer to mount a local directory.

---

## Contributing

Contributions are welcome. Please follow the standard fork-and-pull request workflow.

1.  **Fork** the Project.
2.  **Create** your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the Branch (`git push origin feature/AmazingFeature`).
5.  **Open** a Pull Request.

---

## License & Authors

**Graphite-Phlow**

Copyright © 2025 **Matthew Robert Wesney**.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
