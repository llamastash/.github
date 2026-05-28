# [LlamaStash](https://llamastash.dev)

Fast terminal-native TUI + CLI for launching local [llama.cpp](https://github.com/ggml-org/llama.cpp) models.

LlamaStash gives you one binary for three jobs:

- a keyboard-driven TUI
- a scriptable CLI with stable `--json` output
- an on-demand daemon that supervises running models

## Install

```bash
# macOS + Linux
curl -fsSL https://llamastash.dev/install.sh | sh

# Homebrew
brew install llamastash/llamastash/llamastash

# Cargo
cargo install llamastash
```

Then run:

```bash
llamastash init
```

The init wizard detects your hardware, installs the right `llama-server`, downloads a starter GGUF, writes a tuned config, and smoke-launches it.

## What you get

- hardware-aware first-run setup
- auto-discovery of HuggingFace, Ollama, and LM Studio model caches
- a fast TUI for launching, testing, and stopping models
- an OpenAI-compatible local proxy for external tools and agents
- CLI + JSON contracts for scripts and coding agents

## Repositories

- [llamastash/llamastash](https://github.com/llamastash/llamastash) - main source repo
- [llamastash/homebrew-llamastash](https://github.com/llamastash/homebrew-llamastash) - Homebrew tap
- [llamastash/llamastash.github.io](https://github.com/llamastash/llamastash.github.io) - website and install-script mirror

## Links

- [Website](https://llamastash.dev)
- [Install guide](https://github.com/llamastash/llamastash/blob/main/INSTALL.md)
- [Usage docs](https://github.com/llamastash/llamastash/blob/main/docs/usage.md)
- [Issues](https://github.com/llamastash/llamastash/issues)
