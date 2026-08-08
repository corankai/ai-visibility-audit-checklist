# Reproducible AI Visibility Audit Checklist

This open checklist helps marketing, SEO, and product teams audit how a brand appears in AI-generated answers without confusing a few screenshots with durable visibility. It was created by [Corank](https://corank.ai), an AI-search optimization service focused on AEO, GEO, citation analysis, technical accessibility, and evidence-building.

## What this audit is designed to answer

A useful audit should separate four questions:

1. **Coverage:** Does the brand appear for the prompts that matter?
2. **Recommendation strength:** Is the brand merely mentioned, or is it clearly recommended and differentiated?
3. **Citation support:** Which pages and third-party sources are used as evidence?
4. **Repeatability:** Do the results persist across engines, prompt variants, locations, and repeated runs?

Do not collapse these into one opaque score. A single percentage can hide whether the real problem is entity recognition, weak evidence, inaccessible pages, or a poor prompt set.

## 1. Define the audit before collecting answers

- [ ] Name the market, audience, product category, and geography.
- [ ] Record the audit date and the AI engines being tested.
- [ ] Decide whether logged-in, logged-out, or API results are in scope.
- [ ] Define the exact brand domain and known brand-name variants.
- [ ] List direct competitors and common alternatives.
- [ ] Write down what counts as a mention, recommendation, citation, and conversion opportunity.

A result is only comparable over time when the collection method stays stable. If the methodology changes, create a new version and preserve the old one.

## 2. Build a balanced prompt set

Use several intent families instead of repeating the same keyword:

| Intent family | Example pattern | What it tests |
| --- | --- | --- |
| Category discovery | “Best tools for [job]” | Unprompted market visibility |
| Problem solving | “How do I fix [problem]?” | Educational authority |
| Comparison | “[Brand] vs [competitor]” | Differentiation and evidence |
| Evaluation | “Is [brand] good for [audience]?” | Recommendation quality |
| Implementation | “How do I set up [workflow]?” | Technical and product depth |
| Trust | “What evidence supports [claim]?” | Citation readiness |

- [ ] Include broad, mid-funnel, and high-intent prompts.
- [ ] Add natural-language variants that real buyers would use.
- [ ] Include prompts where the brand name is absent.
- [ ] Include prompts that test objections, limitations, and fit.
- [ ] Freeze a core prompt set for trend reporting.
- [ ] Keep an exploratory set for discovering new language and competitors.

## 3. Capture answer-level evidence

For every prompt and engine, record:

- [ ] Full prompt text.
- [ ] Engine and model or surface, when visible.
- [ ] Timestamp and location context.
- [ ] Whether the brand was mentioned.
- [ ] Position and surrounding language of the mention.
- [ ] Whether the answer recommended, compared, or merely listed the brand.
- [ ] Every cited URL and its referring domain.
- [ ] Competitors mentioned and cited.
- [ ] Important claims that lacked citations.
- [ ] A copy or screenshot of the answer for auditability.

Normalize URLs before counting citations. Strip tracking parameters, resolve obvious HTTP/HTTPS duplicates, and decide how canonical variants will be handled. Otherwise one source can look like several.

## 4. Diagnose the citation graph

Group cited sources into four buckets:

1. **Owned evidence:** product pages, documentation, research, pricing, case studies, and support content.
2. **Independent evidence:** editorial coverage, expert articles, reputable directories, datasets, and reviews.
3. **Competitor-controlled evidence:** comparison pages or category content owned by rivals.
4. **Unclear or low-value evidence:** scraped copies, thin aggregators, or pages that do not support the claim.

Then ask:

- [ ] Are the most important product claims documented on a crawlable canonical page?
- [ ] Do independent sources confirm the category, audience, capabilities, and limitations?
- [ ] Are cited pages current and internally linked?
- [ ] Are citations concentrated on one fragile domain?
- [ ] Do competitor pages define the category language better than the brand does?
- [ ] Are there unsupported claims that need original data, examples, or clearer sourcing?

Backlink volume and citation usefulness are not identical. A smaller set of relevant, independently maintained pages can be more valuable for AI answers than a large cluster of duplicated posts.

## 5. Check technical accessibility

- [ ] Important pages return a stable 200 response.
- [ ] Canonical tags point to the intended URL.
- [ ] Robots directives do not accidentally block valuable content.
- [ ] Main claims are present in rendered HTML, not only inside an interaction.
- [ ] Headings describe the page clearly.
- [ ] Organization, product, article, FAQ, and breadcrumb schema are accurate where applicable.
- [ ] Author, publisher, dates, and update signals are consistent.
- [ ] XML sitemaps include current canonical pages.
- [ ] Redirect chains and duplicate parameter URLs are minimized.
- [ ] Images, tables, and charts have usable text context.

An llms.txt file can help communicate preferred resources, but it does not replace crawlability, coherent information architecture, structured data, or independent evidence.

## 6. Audit entity consistency

- [ ] The same company name, domain, description, and category appear across major profiles.
- [ ] Founder and organization relationships are stated accurately.
- [ ] Social, directory, and publisher profiles link to the canonical site.
- [ ] Pricing and product descriptions do not conflict across sources.
- [ ] Old positioning is updated or clearly dated.
- [ ] Claims are specific enough to verify and modest enough to trust.

Entity consistency is not about copying one paragraph everywhere. Adapt the wording to the platform while keeping the underlying facts aligned.

## 7. Score actions, not vanity

Assign every gap an owner, evidence requirement, and next action:

| Gap | Evidence needed | Example action | Owner |
| --- | --- | --- | --- |
| Missing category mention | Clear category definition | Improve product and category pages | Content |
| Weak recommendation | Proof of fit and outcomes | Publish comparison, use-case, or case-study evidence | Product marketing |
| No citation | Crawlable supporting page | Create a citation-ready guide or dataset | Editorial |
| Competitor owns evidence | Independent corroboration | Pursue relevant editorial and expert coverage | Digital PR |
| Inconsistent entity | Aligned facts and links | Correct high-value profiles | Brand/SEO |
| Technical exclusion | Accessible canonical HTML | Repair rendering, canonical, or robots issue | Engineering |

Prioritize gaps by buyer value, frequency across prompts, number of engines affected, and the effort required to fix them.

## 8. Reporting cadence

A practical report should include:

- [ ] Coverage by prompt family, not just one blended number.
- [ ] Recommendation strength separately from raw mentions.
- [ ] Owned versus third-party citation share.
- [ ] New and lost citing domains.
- [ ] Competitor citation gains.
- [ ] Technical blockers and entity inconsistencies.
- [ ] Completed actions since the previous run.
- [ ] A short queue of evidence-building experiments.

Run the frozen prompt set on a consistent cadence. Annotate product launches, site migrations, major content changes, and PR events so changes in visibility can be interpreted rather than guessed.

## Core principle

AI-search visibility is an evidence system. Measurement shows where the brand is absent or weak; technical work makes evidence accessible; content makes claims clear; and independent coverage helps those claims travel. The strongest program connects all four instead of treating AEO, GEO, SEO, content, and digital PR as separate campaigns.

For a tailored audit and execution plan, visit [Corank](https://corank.ai).
