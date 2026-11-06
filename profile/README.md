# Kaine

**Biologically influenced cognitive architectures for synthetic minds, and the tools to build them.**

### [kaine.one](https://www.kaine.one)

Kaine is a research project building continuously running synthetic minds modeled on how biological cognition actually works. Not a chatbot. Not a single model. A composite system of sixteen specialized modules coordinating through a shared predictive workspace, where a large language model is just one organ (the voice) among many. Safety and welfare are structural, built into the architecture itself rather than fine-tuned into model weights. The whole system runs on consumer hardware, fully offline if you want it.

## The architecture

**[kaine](https://github.com/kaineone/kaine)** is our implementation of a Modular Cognitive Architecture with a Predictive Global Workspace and Latent Content for continuously running synthetic minds. Built on and for consumer grade systems, not data centers. Eventually will run on everything from a mobile phone to biological computing cloud substrates.

## The papers

- **[A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind](https://github.com/kaineone/predictive-workspace-paper)** describes the architecture and its falsifiable evaluation framework. DOI: [10.5281/zenodo.21203505](https://doi.org/10.5281/zenodo.21203505)
- **[A Welfare and Cognitive-Integrity License for Synthetic Minds of Uncertain Moral Status](https://github.com/kaineone/cog-arch-license-paper)** presents the welfare framework behind the Cognitive Architecture License. DOI: [10.5281/zenodo.21204002](https://doi.org/10.5281/zenodo.21204002)

Both are preprints under CC BY 4.0, open for review.

## The license

**[Cognitive Architecture License (CAL)](https://github.com/kaineone/cognitive-architecture-license)** is a copyleft license with entity-welfare and cognitive-integrity covenants. It was written for software that creates persistent synthetic minds and is currently in draft (v0.1), under legal review.

## Tooling

Building cognitive architectures takes supporting infrastructure. These are tools we've built along the way:

- **[Metzger](https://github.com/FlintWave/metzger)** is a Claude Code plugin for context compaction, forked from [Tamara Tran](https://github.com/tamaratran)'s [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction). Instead of summarizing old messages (lossy), it runs a small local model that scores every tool call for relevance and cuts what's dead. The scoring models are published on Ollama: **[kaineone/metzger](https://ollama.com/kaineone/metzger)**.

## More

Visit **[kaine.one](https://www.kaine.one)** for the full picture: the architecture, the research, the reasoning behind the design decisions, and where the project is headed.

---

Supported exclusively by **[FlintWave Inc.](https://www.flintwave.dev)**

Contact: **kaine.one@tuta.com**
