# Bun based Claude Code devcontainer for VSCodium 

## Features

- Based on the [Claude Code development container reference implementation](https://github.com/anthropics/claude-code/tree/main/.devcontainer)
- Uses [Bun](https://bun.sh/) instead of Node.js
- Supports [VSCodium](https://vscodium.com/) with ['DevPod Containers' extension](https://github.com/3timeslazy/vscodium-devpodcontainers)
- Works with [DevPod](https://devpod.sh/)
- tmux installed

## Headless mode
```bash
devpod up . \
  --id my-app \
  --ide none \
  --devcontainer-path .devcontainer/devcontainer.json

ssh my-app.devpod
```
