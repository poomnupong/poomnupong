## Intro

💼 Client Strategist @ Microsoft - manufacturing & automotive
☁️ Azure infrastructure, networking, and the long road from datacenter to edge
🧊 NixOS & nix-darwin on everything I own — laptop, home lab, Azure images
🤖 Local LLMs on Apple Silicon (MLX / oMLX) wired to agentic coding workflows
🛠️ Copilot CLI, GitHub Actions — automation as a first language
🌏 Based in Dallas, frequently somewhere over the Pacific
🇺🇸 🇯🇵 🇹🇭

---

### How I think

**Infrastructure should be declarative, reproducible, and boring** — so the interesting work can happen on top of it. Wipe the machine, re-run the script, get the same setup. If it can't be re-created from a flake and a bootstrap, it doesn't belong in my setup.

**The next decade of computing happens both at cloud and edge** — small, capable models running locally, talking to bigger ones in the cloud only when they need to. Privacy, latency, and cost all point the same direction. I run my own stack end-to-end to learn what that future actually feels like, not just to read about it.

**The best way to understand a tool is to put it in your daily path**. So my MacBook, my home lab, and my Azure tenant are all live experiments — every commit is me learning something I couldn't have learned by reading docs alone.

And lastly: *the world has no border, and none of us has a limit.*. I contribute by showing my clients and peers the path to possibilities.

---

### My work so far

## Development on Linux & Mac

- 🧪 **[`mac-nix-agent`](https://github.com/poomnupong/mac-nix-agent)** — a one-command, nix-darwin recipe that turns a fresh Apple Silicon Mac into a self-contained AI workstation: oMLX for local MLX inference, Hermes Agent in an Apple container microVM, everything reproducible, zero cloud dependency by default but optional burstable.
- 🧱 **[`nixos-azimage-builder`]([https://github.com/poomnupong](https://github.com/poomnupong/nixos-azimage-builder))** — declaratively built NixOS VHDs for Azure, with smoke tests gating promotion through tiers. While having golden image is not how NixOS deployment works - this is more of a proof of concept of how NixOS image building automation would work.

## Azure / Azure Networking notes from previous role

- [Skytap networking overview](https://github.com/poomnupong/azure-networking/blob/main/001-skytap-networking-overview)
- [Understand Azure VM NIC bandwidth consumption matric graph](https://github.com/poomnupong/azure-networking/blob/main/003-understand-azvm-bw-graph)
- [Common Azure Testbed #01 - hub and spoke with deployment pipeline](https://github.com/poomnupong/azure-cat01)
- [Terraform code to set up OpenID Connect between Entra ID and Github Actions](https://github.com/poomnupong/tf-az-ghactions-oidc)

## Github stats

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=poomnupong)](https://github.com/anuraghazra/github-readme-stats)  
![GitHub stats](https://github-readme-stats.vercel.app/api?username=poomnupong&show_icons=true)  

---

### Where I'm heading

- Making **local agentic AI actually practical** for working professionals — not a toy, not a benchmark, an everyday tool.
- Treating my **personal infrastructure as a research lab** for the patterns I want to bring back to the enterprise: declarative, observable, agent-friendly.
- Sharing the **bootstrap scripts, flakes, and lessons** publicly so the next person spends hours, not weeks, getting to the interesting part.

---

### How to engage me

- 🐙 Issues and PRs on any of the repos above — especially `mac-nix-agent`. If you tried it on your Mac and something broke, I want to know.
- 💬 Chat about: AI applications in general, NixOS & Nix on macOS, MLX inference, Hermes Agent, Copilot CLI, agentic CI/CD, Azure landing zones, or just life as Thai-American-in-Japan-sometimes hybrid.

---

*Opinions are my own. Repos are my playground. Everything here is built to be re-built.*

