# Write Like FedRAMP

Use this Codex skill to draft and revise text in FedRAMP’s public writing style. Help readers understand what changed, why it matters to their work, and what they need to do.

Use it to:

- Write requirements that name the responsible party and action, preserve the scope, and keep each obligation’s meaning intact.
- Draft announcements and leadership updates that explain what changed, what has been delivered, and who will do what next.
- Prepare operational notices that make the required action, deadline, conditions, and support route easy to find.
- Explain security problems in plain language, using concrete examples and their effects on government work.

The writing guidance draws on CR26, official FedRAMP communications, Pete Waterman’s signed prose, and interview quotations attributed to him. The November 16, 2026 review expanded the source list with recent notices, milestone updates, and earlier Waterman material. See [references/sources.md](references/sources.md) for links, dates, writing patterns, and limits on what was reviewed. The repository does not include copies of source prose or transcripts.

## Install in Codex

Clone this repository into your personal skills directory:

```sh
git clone https://github.com/gillooleyj/write-like-fedramp.git ~/.codex/skills/write-like-fedramp
```

If you use a custom `CODEX_HOME`, clone into its `skills/write-like-fedramp` directory instead. If that directory already contains the skill, use the existing installation or back it up before replacing it.

The skill will be available on your next turn. Use `$write-like-fedramp`, or ask Codex to write in FedRAMP’s voice.

## Use

```text
Use $write-like-fedramp to rewrite this announcement for cloud service providers.

Use $write-like-fedramp to explain this policy change to agency security teams.

Use $write-like-fedramp to tighten these draft requirements while preserving their meaning.
```

Provide your draft or verified facts, identify the audience, and specify the format. The skill preserves your organization’s perspective without implying that you speak for FedRAMP. You can use it on its own or with the Write Like Me plugin.

## Humanizer editing pass

Before returning a draft, the skill checks for formulaic openings, inflated claims, repeated conclusions, and formatting that gets in the reader’s way. This editing pass adapts guidance from [Humanizer 4.0.0](https://github.com/blader/humanizer) by Siqi Chen.

If Humanizer is installed, the skill uses it for this pass and returns only the finished writing. Otherwise, it uses the editing guidance included in the skill. Both approaches preserve facts, requirement language, official terminology, citations, and meaningful qualifications while keeping the tone appropriate to the document. The pass does not determine authorship or guarantee an AI-detector result.

## Style and policy accuracy

The skill provides writing guidance. It does not assess compliance. It directs Codex to verify current requirements, dates, terminology, and applicability against official sources, with browsing access when verification is needed. Historical interviews and style examples do not override current rules.

This independent community project is not an official FedRAMP or GSA publication. It does not imply endorsement by FedRAMP, GSA, or Pete Waterman.

## Contribute

Open an issue with a concrete writing example or submit a pull request with a focused improvement. Attribute sources clearly and distinguish writing examples from current policy authority. Do not add copied source prose or transcripts.

## License

The instructions and documentation, including the adapted Humanizer guidance, use the [MIT License](LICENSE). The license retains Humanizer's copyright notice. Linked third-party sources remain subject to their own terms.
