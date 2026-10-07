# Agentic AI Token Economics Research Project

This independent research project examines the economic feasibility of agentic AI by comparing token-based operating costs with human labour costs.

The paper analyzes how token usage, tool calls, retries, supervision, infrastructure, compliance, and error correction affect the true cost of agentic AI deployment.

## Abstract

A direct comparison between API token prices and hourly wages makes agentic AI appear unambiguously cheaper, but it leaves out much of the operating model. Agents can make repeated model calls, retrieve context, use paid tools, retry failed steps, and require human review. This paper compares those total task costs with wage time and estimated employer overhead.

The analysis finds the strongest cost advantage in repetitive, high-volume, low-risk digital work. That advantage narrows as context grows, premium models and tools are added, or failures require supervision and correction. The likely economic effect is therefore task-level automation and human-AI collaboration rather than uniform replacement of complete jobs.

## Research Scope

- Compares AI operating costs against labour costs across digital workflow types.
- Separates direct token spend from hidden implementation and supervision costs.
- Evaluates where automation is economically strong, marginal, or inappropriate.
- Discusses how reliability, compliance, and error correction affect real deployment economics.

## Key Finding

Agentic AI is likely to be most cost-effective for repetitive, high-volume, low-risk digital tasks. However, the full cost advantage depends on workflow complexity, human oversight, reliability, and risk.

## Method

The paper uses a scenario-based cost model rather than a live-company experiment. It compares the estimated cost of completing the same task with an AI workflow and with human labour:

```text
Total AI cost = input tokens + output tokens + tools + retries
              + human review + error correction

Total human cost = task time x hourly wage + employer overhead
```

The human examples use U.S. Bureau of Labor Statistics wage data and an illustrative 25% overhead assumption. AI examples use provider prices available when the paper was completed on May 24, 2026.

| Scenario | AI workload | Additional assumptions | Estimated AI cost |
|---|---:|---|---:|
| Simple support task | 8,000 input + 2,000 output tokens | No tools or review | About $0.004-$0.10 |
| Tool-using support task | 8,000 input + 2,000 output tokens | One web search and one file search | About $0.11 |
| Complex technical task | 100,000 input + 30,000 output tokens | Five web searches and two minutes of human review | About $2.66 |

These examples are sensitivity scenarios, not forecasts or production benchmarks. Their purpose is to show which cost components determine the break-even point.

## Limitations

- Provider prices and model capabilities are point-in-time inputs and will change.
- Token and tool estimates are illustrative; actual usage depends on workflow design and failure rates.
- The 25% labour overhead assumption is a simplifying comparison, not a universal employer cost.
- The study does not measure a deployed organization or estimate every integration, security, compliance, liability, or change-management cost.
- Cost alone does not establish that automation is appropriate, especially for high-risk work requiring judgment or accountability.

## Files

- [The Economics of Agentic AI: Token Cost, Human Labour, and the Future of Work](./The%20Economics%20of%20Agentic%20AI_%20Token%20Cost%2C%20Human%20Labour%2C%20and%20the%20Future%20of%20Work.pdf) - full 22-page research paper
- [CITATION.cff](./CITATION.cff) - GitHub-compatible citation metadata
- [CITATION.bib](./CITATION.bib) - BibTeX citation metadata

## Citation

Gomes, N. (2026). *The Economics of Agentic AI: Token Cost, Human Labour, and the Future of Work*. Independent research paper.

Machine-readable BibTeX metadata is available in [CITATION.bib](./CITATION.bib).

GitHub's **Cite this repository** control uses [CITATION.cff](./CITATION.cff) to generate APA and BibTeX citations for the report.
