# BiliDL

Video downloader for bilibili. It's small, fast and beautiful.

## How To Build

### Install Node.js

Install NVM

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```

Install node via NVM

```shell
nvm install 18
nvm use 18
```

_(Optional)_ Set defulat node

```shell
nvm alias default 18
```

Enable corepack to use pnpm

```shell
corepack enable
```

### Install Rust

Install rustup

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Install toolchain

```shell
rustup toolchain install stable
```

_(Optional)_ Set default toolchain

```shell
rustup default stable
```

### Install Dependencies

```shell
pnpm install
```

### Build

To start a dev server, use

```shell
pnpm tauri dev
```

To build this project, use

```shell
pnpm tauri build
```

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/)
- [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
