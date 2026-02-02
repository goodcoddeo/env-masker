# Env Masker

A VS Code extension that specifically masks values in `.env`, `.json`, `.properties`, `plaintext`, files to prevent accidental exposure during screen sharing or streaming.

<img width="583" height="202" alt="image" src="https://github.com/user-attachments/assets/8964f857-ef42-45d3-a531-f3f42fac7795" />

## Features

- **Automatic Masking**: Automatically detects `.env`, `.json`, `.properties`, `plaintext` files and masks values after the `=` sign.
- **Discord-Style Spoilers**: 
  - Values are hidden by default.
  - **Click to Reveal**: Click on a masked value to reveal it.
  - **Persistent**: Once revealed, it stays visible until you close the file or use the "Hide All" command.
- **Toggle Control**: Enable/Disable globally via commands.

## Usage

- **Activate**: Open any `.env`, `.json`, `.properties`, or `plaintext` file that looks like an environment file.
- **Toggle**: Use `Ctrl+Shift+P` -> `Env Masker: Toggle Masking`.
- **Hide All**: Use `Ctrl+Shift+P` -> `Env Masker: Hide All` to re-mask revealed values.

## Installation

1. Download the `.vsix` file from [here](https://github.com/goodcoddeo/env-masker/releases/tag/new-v0.02)
2. In VS Code, go to Extensions -> `...` (Views and More Actions) -> `Install from VSIX...`
3. Select the file.

# 🛠 그 외
> hqnseung / env-masker
https://github.com/hqnseung/env-masker
---------------------------------
이 프로젝트는 원본 `env-masker` 프로젝트에서 json을 지원하도록 수정하여 배포한 것입니다.
원본 프로젝트는 `https://github.com/hqnseung/env-masker`에서 확인할 수 있습니다.

이 프로젝트의 라이센스 또한 Mit License를 따르고 있습니다.

asdf
