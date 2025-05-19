# LaTeX Development Container

This development container provides an environment for developing and building LaTeX documents, specifically for the CV project.

## Features

- Uses the `mingc/latex` Docker image, which includes a full LaTeX installation
- Configured with VS Code extensions for LaTeX development:
  - LaTeX Workshop for compiling and previewing LaTeX documents
  - LaTeX Utilities for enhanced editing
  - Code Spell Checker for catching typos

## Usage

1. Open this folder in VS Code
2. When prompted to "Reopen in Container", click "Reopen in Container"
3. VS Code will build and start the container, then open the workspace inside it
4. Edit your LaTeX files and save to auto-build using XeLaTeX
5. View the compiled PDF using the LaTeX Workshop extension's built-in viewer

## Building Manually

You can manually build the LaTeX document by:

- Using the LaTeX Workshop extension's build commands (accessible via the sidebar)
- Running the XeLaTeX build task (Ctrl+Shift+B / Cmd+Shift+B)
- Running `xelatex resume.tex` in the terminal

## Container Details

- Image: `mingc/latex`
- Workspace mounted at: `/data`
- LaTeX engine: XeLaTeX
