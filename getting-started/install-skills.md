# Install or read upstream skills

The showcase provides a research guide, not its own installable skill. The following are independent upstream projects. Check your AI client's skill discovery instructions and review the source before installation.

## Gold-week

The upstream [README](https://github.com/dfkai/wq-challenge-gold-skill) explicitly documents this command for supported agents:

```bash
npx skills add dfkai/wq-challenge-gold-skill
```

It requires Node.js/npm and runs an external installer. The upstream also documents manual installation by copying the skill directory into a client-supported skills folder. Keep SKILL.md, references and scripts together; reload the client and verify it discovers the skill. Its [SKILL.md](https://github.com/dfkai/wq-challenge-gold-skill/blob/main/SKILL.md) identifies version 1.1.0 and MIT. Optional scripts include authentication, simulation, score checks and a submission workflow requiring human interaction. The manual guide here requires none of those scripts.

## QuantML

The [upstream repository](https://github.com/QuantML-Research/wq-alpha-research) contains a root SKILL.md, field references and scripts. Clone or download it, review it, and put the complete skill folder in a location your AI client supports. Preserve its relative references, reload the client, and check it can find wq-alpha-research. Its field list is a historical reference; confirm availability and semantics in your account.

The upstream README declares CC BY-NC 4.0. Its optional Python tools and examples include authentication and submission code; review them before execution. This guide copies neither upstream skill. Research hypotheses, the prompts and evidence practices in this folder are this portfolio's guidance. Platform checks and permissions take precedence over historical examples.
