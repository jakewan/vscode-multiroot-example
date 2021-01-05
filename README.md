# Visual Studio Code - Multi-Root Workspace Example

This project gives an example of using a multi-root workspace to work with a monorepo in Visual Studio Code. Sections of the codebase may have different settings from one another. The following hierarchy provides an overview.

```bash
workspace.code-workspace  VSCode workspace file referencing the 4 projects
python-foo/               These Python projects use common settings.
├──foo-project-1/
└──foo-project-2/
python-bar/               These Python projects use common settings.
├──bar-project-1/
└──bar-project-2/
```
