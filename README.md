# Hormozi Offers — Codex Skill

A reusable Codex skill for building, auditing, pricing, packaging, naming, and validating differentiated business offers.

The workflow covers market selection, category-of-one positioning, the Value Equation, problem-to-solution mapping, delivery design, bonuses, guarantees, scarcity, urgency, naming, economics, and validation.

## Install

Clone the repository into your Codex skills directory:

```bash
git clone https://github.com/YourFinancialSolutions/hormozi-offers.git ~/.codex/skills/hormozi-offers
```

If the skill is not detected in an existing session, start a new conversation.

## Use

Reference the skill in your prompt:

```text
$hormozi-offers — interview me and build a complete offer for my business.
```

It supports seven operating modes:

- Full build
- Fast draft
- Audit
- Enhancement
- Comparison
- Explain from the book — explain concepts and examples with source page references
- Apply to my business — connect the methodology to your business facts

## Repository structure

- `SKILL.md` — routing, workflow, and operating rules
- `agents/openai.yaml` — skill display metadata and default prompt
- `references/` — 18 modules: eight working procedures, seven book-knowledge modules, a chapter/source map, 16 analyzed book examples, and three original worked offers
- `assets/` — skill icon

## Knowledge base

The skill includes paraphrased notes mapped to all 16 chapters of a supplied 189-page PDF of *$100M Offers*. Page references identify PDF page positions, not printed page numbers. The PDF itself is not included.

The library separates book principles, added implementation tools, and hypothetical business adaptations. It includes known corrections to source calculations and labels the 100-point audit as an implementation tool rather than an author-published scale.

Modules load as needed for the current stage or question. Routine use does not require uploading the book again; exact quotations or details outside the notes require checking the source.

Example prompts:

```text
$hormozi-offers Explain Trim & Stack with source references and an example.
$hormozi-offers Проведи интервью и создай оффер для моего бизнеса.
$hormozi-offers Audit my current offer and prioritize the changes.
```

## Disclaimer

This is an independent, unofficial skill. It uses paraphrased working notes on the methodology in Alex Hormozi’s *$100M Offers*, but it is not affiliated with or endorsed by Alex Hormozi or Acquisition.com. The repository uses paraphrased working guidance and does not promise business results.

## License

[MIT](LICENSE)
