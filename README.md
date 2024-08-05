# LaTeX-template with Integrated Development Environment

This repository contains:

- A development environment for LaTeX that can be used with Visual Studio Code.
- Github actions to produce the pdf document.

## Development Environment

The development environment is set up with a `.devcontainer` configuration that sets up a Docker container with a full [TeX Live](https://www.tug.org/texlive/) installation, which automatically installs the LaTeX Workshop extension in Visual Studio Code. Additionally, the it contains
_It's perfectly fine to use the template without VS Code._

### Prerequisites

- Visual Studio Code
- Docker

### Using the Development Environment

1. Clone the repository.
2. Open the repository in Visual Studio Code.
3. When prompted, choose to reopen the project in the container. If you're not prompted, press `F1`, type `Reopen in Container`, and hit `Enter`.

Once the container is running, you can start editing your LaTeX files in Visual Studio Code. The LaTeX Workshop extension provides a rich editing experience with features like syntax highlighting, document formatting, and build automation.

### Extensions

#### LaTeX Workshop Extension

The LaTeX Workshop extension enhances the LaTeX editing experience in Visual Studio Code. It provides features like building LaTeX projects, viewing PDF files, and autocompletion for LaTeX commands.

#### Other Extensions

Feel free to add or remove the other extensions from the devcontainer.

**The extensions currently are:**

- vscode icons, Bring real icons to your Visual Studio Code
- gitlens, GitLens supercharges your Git experience in VS Code
- trailing spaces, highlight trailing spaces and delete them in a flash!
- latex utilities, An add-on to LaTeX Workshop that provides some fancy features
- vscode-latex, LaTeX language support for Visual Studio Code
- ltex, Grammar/spell checker using LanguageTool with support for LaTeX, Markdown,  and others

## Github Action

To produce a pdf artifact this repository uses a githgub action. The github action can be customised to produce multiple pdfs. To do this please consult the [official action documentation](https://github.com/marketplace/actions/github-action-for-latex).
