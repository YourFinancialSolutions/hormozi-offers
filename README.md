# Hormozi Offers — Codex Skill

A reusable Codex skill for building, auditing, pricing, packaging, naming, and validating differentiated business offers.

The workflow covers market selection, category-of-one positioning, the Value Equation, problem-to-solution mapping, delivery design, bonuses, guarantees, scarcity, urgency, naming, economics, and validation.

## Install

Clone the repository into your Codex skills directory:

```bash
git clone https://github.com/YourFinancialSolutions/hormozi-offers.git ~/.codex/skills/hormozi-offers
```

Restart Codex if the skill is not detected immediately.

## Use

Reference the skill in your prompt:

```text
$hormozi-offers — interview me and build a complete offer for my business.
```

It supports five operating modes:

- Full build
- Fast draft
- Audit
- Enhancement
- Comparison

## Repository structure

- `SKILL.md` — routing, workflow, and operating rules
- `agents/openai.yaml` — skill display metadata and default prompt
- `references/` — focused guidance for pricing, value, construction, bonuses, guarantees, scarcity, urgency, naming, interviews, and output

## Disclaimer

This is an independent, unofficial skill. It is inspired by publicly discussed offer-building concepts associated with Alex Hormozi and *$100M Offers*, but it is not affiliated with or endorsed by Alex Hormozi or Acquisition.com. The repository uses paraphrased working guidance and does not promise business results.

## License

[MIT](LICENSE)
