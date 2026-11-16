# First research cycle

## 1. Select a research question

Choose an economic idea such as whether profitability relates to future returns. In BRAIN, verify your region, universe, delay, field definitions, units, coverage and available operators. Record unknowns. Give those verified inputs to your assistant.

Use the platform's DATA view to search a field name and open its description. Use the operator documentation or editor search to inspect argument order. Availability and exact screen labels depend on the account and platform version. Record the field ID and description privately.

### Prompt 1: first research

```text
Help me design my first BRAIN research cycle.
Inputs:
- Economic question and rationale: [describe]
- Verified fields, descriptions and units: [paste]
- Region, universe, delay, available operators and settings: [paste]
- Applicable Challenge requirements: [paste or unknown]
Output:
1. A falsifiable hypothesis and competing explanation.
2. At most three distinct candidates using verified inputs, with rationale, expected direction, field requirements and proposed complete settings. Flag unknown syntax or units.
3. A simple baseline or matched comparison and what result would change the conclusion.
4. A results table I can fill in.
Human review: I will verify expressions, settings and field semantics in BRAIN before acting. Do not simulate or submit.
```

## 2. Simulate manually

Choose one or two candidates with different hypotheses. Enter a reviewed expression in the BRAIN Simulation editor. Check actual Settings, including region, universe, delay, neutralization, decay, truncation and available missing-value controls. Run the simulation yourself and wait for completion. Preserve any error or warning.

## 3. Save the evidence

In a private record save the date, hypothesis, expression, actual settings and simulation dates. Copy IS aggregate metrics, annual rows if available, and every PASS, FAIL, WARNING and PENDING with its threshold. Record the official Self-Correlation value, check time and ACTIVE context when available. Keep platform IDs and expressions private; do not invent missing values.

### Prompt 2: analyze simulation results

```text
Analyze my actual BRAIN simulation.
Inputs: hypothesis and baseline [paste]; actual settings and dates [paste]; IS summary, annual results and every check with threshold [paste]; Self-Correlation time and ACTIVE context [paste or unknown].
Output: separate observations, hypotheses and unknowns; explain failures and pending checks; compare annual behavior and baseline if available; identify missing evidence and one or two next questions. Consider coverage, units, turnover and sub-universe issues only where supported. Do not call examined IS data independent out-of-sample evidence.
Human review: I will verify platform numbers and decide what to do. Do not invent results or submit.
```

## 4. Plan the next experiment

### Prompt 3: next controlled experiment

```text
Design the smallest informative next experiment.
Inputs: prior hypothesis, actual expression/settings and result [paste]; competing explanations and failure [paste]; verified fields/operators and baseline results [paste or unknown].
Output: a competing hypothesis and discriminating observation; a baseline and at most two candidates with exact proposed settings and a table of changes; expected failure modes and checks on data/units; a decision rule to continue, stop or investigate missing evidence.
Human review: I will check all expressions and settings and manually decide whether to simulate. Do not submit.
```

Save the new hypothesis beside the earlier result. Before any eventual submission, read current official checks against the current ACTIVE set; submission can change later correlation checks. You make the final submission decision.
