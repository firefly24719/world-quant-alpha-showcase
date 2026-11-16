# WorldQuant BRAIN Alpha Research Portfolio

**WorldQuant Challenge Gold Level** | Research, experimentation and Python engineering

I built an evidence-led research workflow to discover, test and manage quantitative signals under changing correlation constraints. The work combines economic hypotheses, platform experiments, AI-assisted research and a Python pipeline for reproducible records.

## Gold Achievement

**WorldQuant Challenge Gold Level**, awarded to XIE.DONGJIE.

[![WorldQuant Challenge Gold Level certificate awarded to XIE.DONGJIE](assets/gold_certificate_preview.png)](assets/gold_certificate.pdf)

[View the original certificate PDF](assets/gold_certificate.pdf) | [Certificate details and verification](achievement/worldquant_gold.md)

![Research workflow](assets/research_pipeline.svg)

## Evidence at a glance

- **Gold Level** in the WorldQuant Challenge, supported by the certificate above.
- **146 completed simulations** in one documented group of research waves: 107 discovery candidates, 33 field probes and 6 controls.
- A later local pool contained **140 candidate expressions**, of which **132 passed static checks**. These are not 132 successful platform Alphas.

## What the research demonstrates

Signals that look different in code can generate similar returns. Adding a successful Alpha changes the comparison set for every remaining candidate. The research workflow therefore records economic hypotheses, examines dated daily returns, and refreshes platform checks as the submitted portfolio changes.

| Research decision | Evidence and lesson |
|---|---|
| [Alpha redundancy](research/selected_case_studies/01_alpha_redundancy.md) | A previously passing candidate failed after a related Alpha was submitted. |
| [Dynamic correlation](research/selected_case_studies/02_dynamic_correlation.md) | Submission order can matter when a higher-Sharpe candidate qualifies for the platform's improvement exception. |
| [Mechanism identification](research/selected_case_studies/03_mechanism_identification.md) | A price control challenged an initially attractive interpretation of trading-activity information. |

## How the system works

The Python research system tracks candidate provenance, actual settings, platform checks and analysis outputs. AI assists with literature review, hypothesis development, implementation and interpretation. Platform simulations provide the observed results, and submission remains a human decision.

![System architecture](assets/architecture.svg)

Explore the [research methodology](research/methodology.md), [discovery overview](research/discovery_overview.md), [system architecture](engineering/system_architecture.md) and [evidence and metrics](docs/evidence_and_metrics.md). The [limitations](docs/limitations.md) explain what these results establish. Methods adapted from two community research skills are credited in [references](docs/references.md).

This portfolio presents the research and achievement. Concrete factor expressions, Alpha identifiers, account-linked PnL, credentials and the private research ledger are excluded.
