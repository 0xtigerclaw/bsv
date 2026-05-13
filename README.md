# BSV AI Landscape and Diligence Prioritization

This repo contains a single-page HTML artifact for the BSV AI Fellow written project:

- `bsv_ai_landscape_diligence_prioritization.html`

The artifact ranks eight AI companies for deeper diligence from BSV's perspective and explains how each company fits into the broader AI systems landscape and BSV's existing portfolio.

## Core Framing

I treated the assignment as a portfolio-management question, not just a company-comparison exercise.

The question I optimized for was:

> Which company should BSV spend the next serious diligence cycle on, given the company's standalone promise, its position in the AI stack, and its potential relationship to the existing BSV portfolio?

That means the ranking is not a final investment recommendation. It is a diligence-priority view: a way to decide where deeper product testing, buyer interviews, competitive mapping, and founder diligence should happen first.

## Ranking Rationale

The framework uses five criteria:

1. **Portfolio edge**  
   Does the company strengthen, explain, or create leverage for BSV's existing AI portfolio? A company is more interesting if it can become a shared infrastructure layer, workflow primitive, or learning node across other BSV companies.

2. **AI system centrality**  
   Where does the company sit in the AI stack? I favored companies that sit near bottlenecks or coordination points: inference, memory, structured outputs, state, developer context, and agent workflows.

3. **Value capture potential**  
   Can the company become a durable control point, or is it likely to be absorbed by model providers, hyperscalers, open-source frameworks, or internal tooling?

4. **Standalone company quality**  
   Does the company show credible public signals: clear product, sharp target customer, community pull, technical differentiation, category timing, and funding attractiveness?

5. **Diligence leverage**  
   Would a focused diligence sprint materially change conviction? I prioritized companies where hands-on testing and customer/market research could quickly clarify whether the opportunity is exceptional or merely plausible.

## Ranked Companies

| Rank | Company | Why It Ranked There |
| --- | --- | --- |
| 1 | BAML / BoundaryML | Highest diligence priority because structured outputs and AI reliability are central to production AI systems. It also creates a clear testing surface against native model-provider tools, Instructor, Pydantic AI, and hand-rolled prompting. |
| 2 | Mem0 | Strong systems position because memory and personalization are likely to become core agent infrastructure. The key diligence question is whether it becomes a durable memory layer or a feature absorbed by frameworks and model providers. |
| 3 | Parasail | Central to inference economics, which affects nearly every AI application. The company is strategically important if it can prove durable advantage in cost, latency, capacity, or workload placement. |
| 4 | Tigris Data | Relevant portfolio infrastructure node for storage-heavy AI workloads. The diligence question is whether AI-specific object storage creates enough differentiation versus S3, GCS, R2, and adjacent storage platforms. |
| 5 | Entire | Interesting if agentic software development becomes a new operating layer for engineering teams. It ranks below core infrastructure because the category and wedge still need sharper validation. |
| 6 | Atuin | Strong developer workflow product with community pull. Its AI relevance depends on whether shell history and developer context become a meaningful layer for coding agents and dev automation. |
| 7 | Rasa | Important enterprise-agent reference point, but more mature and less asymmetric for this specific early-stage diligence exercise. It is useful as a comparison case for agent orchestration and enterprise adoption. |
| 8 | Primitive | Conceptually relevant for agent communication, but currently the hardest to underwrite from public information. It needs clearer evidence of wedge, adoption, and value capture. |

## Thinking Process

I started by mapping the AI landscape as a five-layer system:

1. Compute and model foundation
2. Data, state, and memory
3. Reliability and interfaces
4. Agentic development and context
5. AI work applications

Then I placed BSV portfolio companies and the target diligence companies into that system. The important step was not only assigning categories, but mapping interdependence: which companies enable, depend on, reinforce, or overlap with each other.

That systems view changed the ranking logic. A company did not move up only because it looked like a good standalone startup. It moved up if it also sat near a leverage point in the AI stack or helped explain where BSV's portfolio could compound.

I also separated **GTM support leverage** from the main ranking. A company may be very supportable by BSV from a GTM perspective without being the top diligence target. Keeping those separate avoids turning the ranking into a marketing-support list.

## GTM Support Lens

The artifact annotates GTM support leverage but does not let GTM potential dominate the ranking.

The strongest later Track 2 GTM candidate is currently **BAML / BoundaryML** because:

- The product has a clear developer audience.
- The category needs education around structured outputs and AI reliability.
- Public docs, examples, repos, and competitor pages create useful material for a GTM agent.
- The GTM problem is concrete: turn technical differentiation into developer adoption.

Secondary GTM candidates are **Mem0**, **Parasail**, **Tigris Data**, and **Entire**, depending on whether the later GTM deep dive is optimized for category creation, infrastructure positioning, or portfolio-wide usage.

## Limitations

This analysis uses public information and product-facing evidence. It does not replace private diligence.

The main limitations are:

1. It relies on inferred signals rather than private traction, revenue, customer references, and founder diligence.
2. The systems map shows plausible interdependence, but does not quantify dependency strength or actual portfolio usage.
3. The ranking is a diligence-priority view, not a final investment view, until tested against hands-on product work, buyer interviews, competitive depth, and funding context.

## How To View

Open the HTML file directly in a browser:

```text
bsv_ai_landscape_diligence_prioritization.html
```

The page is intentionally desktop-first and includes theme/font controls for experimenting with the final look and feel.
