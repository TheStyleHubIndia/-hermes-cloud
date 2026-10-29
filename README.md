# Hermes Agent Cloud (GitHub Codespaces)

This repository is prepared for a browser-based Hermes Agent environment. No Termux is required.

## Start it on Android

1. Open the repository: https://github.com/TheStyleHubIndia/-hermes-cloud
2. Tap **Code** → **Codespaces** → **Create codespace on main**.
3. Wait for the Codespaces environment to finish building. The `.devcontainer/devcontainer.json` runs the official Hermes Agent installer after creation.
4. Open **Terminal → New Terminal** and check:
   ```bash
   hermes --help
   ```
5. Start first-time configuration:
   ```bash
   hermes setup
   ```
6. Follow the prompts in the terminal. Then check available commands with `hermes --help`.

## Important limitations

- Codespaces is a development environment, not a guaranteed always-on 24/7 server. Free usage has monthly quotas and the environment can stop when idle.
- Do not paste API keys, OAuth tokens, Google client secrets, or YouTube refresh tokens into this repository or chat. Enter secrets only in the appropriate private setup prompt or secret store.
- Hermes installation does **not** by itself connect YouTube or schedule uploads. YouTube automation requires separate Google OAuth/API configuration and explicit testing.
- No video has been uploaded or scheduled by this repository setup.

## Official references

- Hermes Agent installation: https://hermes-agent.nousresearch.com/docs/getting-started/installation
- Hermes Agent installer: https://hermes-agent.nousresearch.com/install.sh
- YouTube Data API: https://developers.google.com/youtube/data/getting-started
