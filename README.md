# pnpm-template

A minimal project template ready to run in GitHub Codespaces with the latest LTS Node.js version and the latest stable pnpm release.

## Features

- Node.js LTS (v22)
- pnpm v10.22.0
- GitHub Codespaces support
- ES Modules by default

## Getting Started

### In GitHub Codespaces

1. Click the "Code" button on this repository
2. Select "Open with Codespaces"
3. Click "New codespace"

The development environment will be automatically configured with the correct Node.js and pnpm versions.

### Locally

1. Ensure you have Node.js v22 installed (or use nvm: `nvm use`)
2. Install pnpm: `npm install -g pnpm@10.22.0`
3. Install dependencies: `pnpm install`

## Project Structure

```
.
├── .devcontainer/        # GitHub Codespaces configuration
│   └── devcontainer.json
├── .nvmrc                # Node.js version specification
├── .npmrc                # pnpm configuration
├── package.json          # Project metadata and dependencies
└── README.md             # This file
```

## License

MIT