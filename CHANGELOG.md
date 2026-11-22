# Changelog — OmegaAPI AI

Install: [Open VSX](https://open-vsx.org/extension/OmegaAPI/omegaapi-ai) · Buy / renew: [omegaapi.in/product/omega-ai](https://omegaapi.in/product/omega-ai)


### 1.1.0
- **Licensing moved to omegaapi.in.** Activation/verification now use `omegaapi.in/api/omegaai`; the old `ai1.omegaapi.com` PHP server was retired. Device-bound, server-is-source-of-truth. Renewals and revocations from the admin panel reach the extension automatically.
- **New pricing:** single **Pro** plan — $251 one-time setup fee with 3 years of updates & new releases (replaces the old monthly/lifetime/enterprise tiers). Existing keys keep working.
- **Real-time file generation** — files are written live in the editor while the AI streams them (like Cline / OpenCode). Cancelling mid-file restores the original.
- **Checkpoints / one-click undo** — the original of every file the AI touches is snapshotted; undo a turn, review the before/after diff, or restore the project to any earlier point (`Omega: Restore Checkpoint`).
- **Secret leak protection** — API keys, passwords, tokens and `.env` files are redacted before anything reaches the model, and the real values are restored when the AI writes a file back. `.env` and key files are never read.
- **Automatic RAM / VRAM model management** — detects CPU, RAM, GPU and VRAM (NVIDIA, AMD, Apple Silicon); the model picker shows whether each model fits (GPU / split / CPU / too big) and recommends the best one; the context window is sized to free memory; unused Ollama models are unloaded. New commands: `Omega: System Info`, `Omega: Free RAM/VRAM`.
- **Command confirmation** — the AI asks before running any terminal command (toggle with `omega.autoRunCommands`).
- Removed the admin key-generator command from the extension (keys are issued only from the omegaapi.in admin panel).

### 1.0.x — bug fixes
- Commands were being executed twice (once in a terminal, once captured) — now run once with output in the "OmegaAPI Agent" panel.
- The agent could overwrite existing files from a small code snippet, and could write outside the workspace — writes are now confined to the workspace and code-block files never overwrite existing files.
- Tool-call loop fed the model its own accumulated reply repeatedly — now only the new turn is sent, with a hard loop cap.
- Server errors (model not found, bad endpoint) showed as an empty reply — now a clear error message.
- `temperature: 0` was treated as unset (fell back to 0.7) — fixed.
- Sending a second message mid-response mixed the two replies — now blocked until the first finishes.
- "That's wrong" corrections were learned against the wrong (new) answer — now against the previous one.

