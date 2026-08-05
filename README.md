# J. Alderman Lyell

I write, and I ship software. The two are the same job more often than people expect.

Most of what's here started as a problem in a business I was running. The radon company needed inspection reports that didn't take an afternoon each, so I built the generators. A short-form video series needed a production pipeline that could hold a character's face consistent across a hundred episodes, so I built that. I direct AI coding agents to do the implementation and I own what goes in.

## What's here

### [vintage-study](https://github.com/wolfvswhale/vintage-study)

Does a machine-text detector get worse as the generator gets newer? Everyone assumes so. Across eighteen generators released between 2019 and 2025, it does not: within a fixed corpus the correlation runs the other way. What does predict detectability is instruction tuning, by 26 to 29 points on same-family, same-date model pairs.

### [bluepencil](https://github.com/wolfvswhale/bluepencil)

A quality gate for prose. Eighteen gates, every threshold set by measuring the statistic across 2,602 human-written documents so the false-positive rate is a measured 5% rather than a guess. Fails 46.9% of machine-written documents and 6.3% of human ones. Nine gates don't discriminate on the available corpus, and the README publishes those numbers too.

### [prose-eval](https://github.com/wolfvswhale/prose-eval)

The evaluation harness underneath it. Structural cadence carries nearly all the signal; the corpus turned out to have a detokenization artifact separating the classes on 73% of documents; and the fitted model transfers *below chance* to a new domain. The repo documents that failure rather than reporting the in-domain score alone.

### [airtable-automation-portfolio](https://github.com/wolfvswhale/airtable-automation-portfolio)

Three live business systems: a lead-scoring CRM with auto-routing, milestone invoicing synced to QuickBooks Online, and a legacy data migration that turned a 113-row export into 89 clean typed records while preserving 21 that naive deduplication would have dropped. Screenshots and a reconciled invoice, not mockups.

### [ai-persona-video-pipeline](https://github.com/wolfvswhale/ai-persona-video-pipeline)

The generative video system behind a running short-form series. Remotion, Replicate, ElevenLabs, Python, Airtable for production tracking. Sanitized: it's a live commercial series under a pen name, so the persona assets and working tree stay private.

## Elsewhere

## Elsewhere

I write up what I find at **[wolfvswhale.github.io](https://wolfvswhale.github.io)** — short, evidence-first reviews of how machine-text detection gets evaluated, each one linking the code and data behind it.

Long-form historical documentary on YouTube, where I do the research, the script, the edit, and the publish. Books on Amazon under two names. Four years as a digital court reporter before any of this, which is where I learned that a transcript is a product and accuracy is the whole product.

## Working with

Python, JavaScript, Node. Claude Code and agentic tooling daily. n8n and Airtable for automation. Remotion, Replicate, ElevenLabs for generative media. React Native and EAS for the iOS side.

Open to remote work. Best reached at jesselyell1@gmail.com
