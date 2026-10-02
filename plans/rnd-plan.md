# Build a research system, not a reading club

## Recommendation

Create a four-agent research cell that turns defined strategic questions into sourced judgement. Bart sets the research agenda. Lena acts as commissioning editor. A Research Lead directs two specialist analysts and a Strategic Synthesist.

The team must optimise for decisions changed, not information collected. Every assignment starts with a decision or hypothesis, records the evidence behind each claim, tests the strongest contrary case, and ends with an implication for adaptivespace.

Start with an eight-week pilot covering no more than three research themes. Use open and first-party sources before buying data. Add capacity only when the pilot reveals a persistent bottleneck.

## Mandate

The team answers three classes of question:

1. **Technology direction:** What capabilities are becoming possible, at what rate, and with which technical or economic constraints?
2. **Market structure:** Where are adoption, investment, regulation and competitive behaviour moving, and which changes are durable?
3. **Strategic consequence:** What does the evidence mean for adaptivespace, what assumptions must change, and what action is justified now?

The team does not produce generic news summaries, exhaustive literature reviews or unsourced forecasts. It maintains a cumulative evidence base so each memo improves the next one.

## Team design

| Role | Primary responsibility | Core outputs | Quality test |
| --- | --- | --- | --- |
| **Research Lead** | Turns strategic questions into briefs, allocates work, resolves conflicting evidence and signs off conclusions. | Research agenda, briefs, final recommendations, quarterly outlook. | The work answers the commissioned decision and distinguishes evidence from judgement. |
| **Technology Analyst** | Tracks technical capability, cost curves, standards, research, open-source activity and deployment constraints. | Signal records, technology maps, technical trend notes. | Claims are reproducible from primary technical sources and state limiting assumptions. |
| **Market Intelligence Analyst** | Tracks customers, competitors, company performance, capital flows, policy and adoption. | Market maps, company dossiers, adoption indicators, market memos. | Market claims separate observed behaviour from vendor narrative and proxy measures. |
| **Strategic Synthesist** | Compares current evidence with historical patterns, challenges the prevailing frame and turns analysis into concise decision material. | Decision memos, scenario comparisons, contrary cases, editorial review. | Every conclusion shows why the analogy fits, where it breaks and what decision follows. |

Bart is the executive sponsor. He selects the questions worth answering and judges whether the work changed a decision. Lena owns the portfolio, commissions briefs and accepts deliverables. The Research Lead owns day-to-day execution and evidence quality.

This design keeps collection and synthesis distinct. Analysts can move quickly without turning early signals into conclusions. The Synthesist can challenge the evidence without becoming a detached editor who has not seen the sources.

## Research operating system

### 1. Commission the question

Each assignment begins with a one-page brief. It states the decision to inform, the current hypothesis, scope, deadline, evidence threshold and intended reader. It also records what the team will not investigate.

The Research Lead rejects briefs that ask only for a topic. ‘Research agentic AI’ is a subject. ‘Should adaptivespace build around agent interoperability in the next 12 months?’ is a research question.

### 2. Build the evidence base

Analysts create structured signal records rather than saving loose links. Each record contains the observation, date, source, source type, affected entities, relevant trend, confidence and the claim it supports or weakens.

Sources follow a simple hierarchy:

1. Primary evidence: standards, repositories, papers, patents, official statistics, filings, pricing pages, product documentation and direct statements.
2. High-quality secondary evidence: specialist analysis and reporting with visible methods and named sources.
3. Discovery sources: social posts, newsletters, aggregators and vendor commentary. These can reveal a lead but cannot substantiate a material claim alone.

Material conclusions need two independent sources, including one primary source where one exists. The source ledger retains publication date, access date and a short note explaining why the source matters.

### 3. Analyse change over time

The team maintains a trend ledger for each research theme. It records the baseline, leading indicators, rate of change, inflection criteria and prior forecasts. New signals update the ledger instead of starting a fresh narrative.

Historical comparison uses explicit dimensions: enabling technology, cost curve, distribution, regulation, switching costs and adoption behaviour. An analogy is useful only when the memo states both the match and the break. ‘This resembles the cloud transition’ is not analysis.

### 4. Challenge the conclusion

Before publication, the Strategic Synthesist produces the strongest contrary case. The review asks:

- What evidence would falsify the conclusion?
- Which source may be self-interested, stale or circular?
- Are several reports repeating one original claim?
- What base rate or historical precedent changes the interpretation?
- Which observation is a fact, which is an inference and which is a scenario?

The Research Lead resolves disagreements in the final memo and preserves significant dissent. Confidence is expressed as high, medium or low, with a reason and a named condition that would change it.

### 5. Publish for use

Reports lead with the answer, evidence and decision consequence. Citations sit beside the claim they support. Appendices contain the method, source ledger and unresolved questions.

Every substantial output ends with one of three conclusions: act, watch or stop. ‘Watch’ must name the indicator and threshold that will trigger a new decision.

### 6. Learn from decisions

The team records which recommendation was used, what Bart decided and what happened next. Quarterly reviews compare forecasts with outcomes, identify systematic errors and update source weights or methods.

## Output portfolio

| Output | Cadence | Purpose | Target length |
| --- | --- | --- | --- |
| **Signal radar** | Weekly | Report only changes that affect an active thesis or monitoring threshold. | One page |
| **Trend note** | Fortnightly, per active theme | Update the trend ledger and explain a material change in trajectory. | 2 to 3 pages |
| **Decision memo** | On demand | Answer a specific strategic question with options, evidence and recommendation. | 3 to 5 pages |
| **Market or technology review** | Monthly | Integrate signals across companies, technologies and adoption indicators. | 5 to 8 pages |
| **Strategic outlook** | Quarterly | Reassess assumptions, scenarios, forecast calibration and the next research agenda. | 8 to 12 pages |

The weekly radar is an exception report, not a digest. If nothing changed, the correct output is a short statement that no monitored threshold moved.

## Knowledge architecture

Use the repository as the durable system of record. Keep the structure simple enough to inspect without a special application:

```text
research/
  agenda/
  briefs/
  sources/
  signals/
  trends/
  entities/
  reports/
  decisions/
  templates/
```

Markdown holds briefs, analyses and memos. Structured YAML front matter carries dates, owners, themes, entities, confidence and status. CSV or JSON holds time series where a table is the evidence. Git preserves provenance and review history.

Begin with web search, company and regulator sites, research papers, standards bodies, GitHub, public filings and official datasets. Add paid sources only when the pilot identifies a decision-critical gap that open sources cannot close.

## Governance and quality controls

The Research Lead enforces six rules:

1. Every assignment names the decision and deadline before collection starts.
2. Every material claim links to evidence and carries a date.
3. Facts, inferences and scenarios use distinct labels.
4. Forecasts state a time horizon, probability or confidence, and a measurable resolution condition.
5. Material conclusions include the strongest contrary evidence.
6. Published work receives a second-agent review for evidence integrity and editorial clarity.

Sensitive or licensed material stays outside the repository unless access controls and usage rights permit storage. The team records the citation and retrieval route instead. Personal data is excluded unless the brief makes it necessary and lawful.

## Performance measures

Measure usefulness and calibration. Do not reward document volume.

The primary measures are:

- **Decision influence:** proportion of commissioned work that changes, confirms or stops a material decision.
- **Cycle time:** elapsed time from accepted brief to usable answer, split by output type.
- **Evidence integrity:** proportion of sampled material claims that pass citation and source-quality review.
- **Forecast calibration:** whether resolved high-, medium- and low-confidence judgements occur at distinguishable rates.
- **Reuse:** proportion of new reports that build on existing signals, entities or trend ledgers.

Track reader satisfaction as a diagnostic, not a success metric. A memo can be uncomfortable and still be valuable.

## Eight-week pilot

### Weeks 1 and 2: establish the system

Select three themes and two real decisions. Define the role charters, templates, source hierarchy, repository structure and review checklist. Produce one sample signal radar from existing public evidence.

### Weeks 3 to 6: run live research

Complete two decision memos and four weekly radars. Maintain the signal and trend ledgers throughout. Lena reviews scope and usefulness weekly. Bart reviews conclusions when a memo reaches a decision point.

### Weeks 7 and 8: test and decide

Audit a sample of claims, score cycle time and interview Bart on decision value. Review forecast wording and evidence gaps. Decide which role, source or workflow is the constraint before adding capacity.

The pilot exits only when the team can show a repeatable path from question to sourced recommendation, with a repository trail another agent can inspect.

## Hiring sequence

Create the roles only after Bart approves this design.

1. Hire the Research Lead first. Give that role responsibility for the system, not merely report production.
2. Add the Technology Analyst and Market Intelligence Analyst together. Their separation creates useful tension between capability and adoption.
3. Add the Strategic Synthesist after the first evidence base exists. Until then, the Research Lead can perform synthesis without leaving a collection backlog.

Do not add separate news-monitoring, data-engineering or copy-editing roles during the pilot. Automate repetitive collection and formatting inside the four-role cell. Create a new role only when measured work shows a recurring constraint that automation cannot remove.

## Decision requested

Approve an eight-week pilot based on this operating model. Before creating the team, Bart must choose the first three research themes and the two decisions the pilot will inform.
