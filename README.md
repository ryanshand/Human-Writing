# Human Writing

Human Writing is a Codex plugin for drafting and rewriting natural, specific, voice-consistent prose. It supports general writing and fiction, preserves supplied facts and deliberate voice choices, and returns only the finished prose unless another output format is requested.

Its editing guidance combines surface-level prose diagnostics with narrative-craft checks informed by [StoryScope](https://github.com/jenna-russell/storyscope). The research is used as a writing diagnostic, not as proof of authorship or a detector-evasion system.

## Install in Codex

Add this repository as a marketplace, then install the plugin:

```powershell
codex plugin marketplace add ryanshand/Human-Writing
codex plugin add human-writing@human-writing
```

Start a new Codex task after installation so the skill is loaded.

## Use

Ask Codex to use `$human-writing`, for example:

- `Use $human-writing to rewrite this in my voice and return only the final prose.`
- `Use $human-writing to draft a natural announcement from these facts.`
- `Use $human-writing to revise this story without flattening its voice.`

## What it does

- Drafts and rewrites general prose and fiction.
- Preserves concrete facts, required meaning, story facts, terminology, and voice.
- Removes padding, boilerplate, unsupported promotional framing, and chatbot residue.
- Treats narrative research as overlapping signals rather than universal rules.
- Avoids claims of human authorship, detector evasion, and imitation of named living authors.

## License

MIT. See [LICENSE](LICENSE).
