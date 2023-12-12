My own personal VSCode theme.

### Setup

```bash
npm install -g @vscode/vsce
```

### Package and Install

```bash
# Generate .vsix extension package
vsce package

# Install as extension
code --install-extension ryan-vscode-theme-0.0.1.vsix
```