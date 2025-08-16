# Environment Setup

## Install Node Version Manager (NVM)

1. Download and install NVM:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

2. Reload your shell configuration:

```bash
source ~/.bashrc
```

3. Verify NVM installation:

```bash
nvm --version
```

## Install Node.js and npm

1. Install the latest LTS version of Node.js (includes npm):

```bash
nvm install --lts
```

2. Verify Node.js and npm installation:

```bash
node --version
npm --version
```

## Install vsce

```
npm install -g @vscode/vsce
```

## Package and Publish the Extension

```
vsce login <publisher id>
vsce package
vsce publish
```

