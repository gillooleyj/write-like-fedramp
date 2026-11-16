# Write Like FedRAMP

A reusable Codex skill for drafting and editing in FedRAMP’s clear, practical public writing style.

It supports four registers:

- **Rules and requirements:** explicit actors, actions, scope, and carefully preserved requirement language.
- **Announcements and leadership updates:** what changed, what has been delivered, and who will do what next.
- **Operational notices:** who needs to act, by when, under which conditions, and where to get help.
- **Conversational explainers:** concrete problems, plain language, and connections to government mission delivery.

The skill draws on CR26 guidance, official FedRAMP communications, Pete Waterman’s signed prose, and attributable interview quotations. The November 16, 2026 review added recent notices and milestone writing alongside older Waterman material that expands the original source set. Source links, dates, useful writing patterns, and review limits are documented in [references/sources.md](references/sources.md). Source prose and transcripts are not bundled.

## Install in Codex

Clone this repository into your personal skills directory:

```sh
git clone https://github.com/gillooleyj/write-like-fedramp.git ~/.codex/skills/write-like-fedramp
```

If you use a custom `CODEX_HOME`, clone into its `skills/write-like-fedramp` directory instead. If that directory already contains the skill, use the existing installation or back it up before replacing it.

The skill will be available on your next turn. Invoke it explicitly with `$write-like-fedramp`, or ask Codex to write in FedRAMP’s voice.

## Use

```text
Use $write-like-fedramp to rewrite this announcement for cloud service providers.

Use $write-like-fedramp to explain this policy change to agency security teams.

Use $write-like-fedramp to tighten these draft requirements while preserving their meaning.
```

Supply the text or verified facts, audience, and desired format. The skill keeps your organization’s perspective and does not imply that you speak for FedRAMP. It works independently; the Write Like Me plugin is optional.

## Style and policy accuracy

This is a writing skill, not a compliance engine. It instructs the agent to verify current requirements, dates, terminology, and applicability against official sources. Historical interviews and style examples do not override current rules. Browsing access is needed when those facts require verification.

This is an independent community project, not an official FedRAMP or GSA publication, and it does not imply endorsement by FedRAMP, GSA, or Pete Waterman.

## Contribute

Open an issue with a concrete writing example or a pull request with a focused improvement. Keep source attribution clear, preserve the distinction between style and policy authority, and avoid adding copied source prose or transcripts.

## License

The original skill instructions and documentation are available under the [MIT License](LICENSE). Linked third-party sources remain subject to their own terms.
