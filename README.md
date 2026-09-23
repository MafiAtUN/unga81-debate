# UNGA81 General Debate — public analysis site

Static site for an analysis of what Member States said in the general debate of the
eighty-first session of the United Nations General Assembly, read against every
general debate since 1946.

## Nothing is published yet

This repository is **private** and GitHub Pages is **not enabled**. There is no
site at `mafiatun.github.io/unga81-debate` and no analysis figure has been
published anywhere.

The analysis is built in a separate private repository. **Only the built static
site is ever copied here** — no speech corpus, no databases, no analysis code, and
no internal Office material.

## Why it is not published

The debate runs 22–26 and 28 September 2026. Publication waits on:

- the debate closing, and coverage reaching the threshold the methodology sets;
- validation of the topic measurement against human coders;
- clearance by the Office of the President of the General Assembly of the
  disclaimer and of the wording used for named situations.

Until then this repository holds only the deployment workflow.

## What will be here

| | |
|---|---|
| `index.html`, `_app/`, assets | the built site |
| `data/{version}/` | the data behind every chart, one directory per released data version, so an old link keeps reproducing its own numbers |
| `.github/workflows/pages.yml` | uploads the committed static files and deploys them. **No build step runs here** |

## Corrections

Once published, every figure on the site will resolve to the sentences it was
computed from, and each will link to the official source page on
`gadebate.un.org`. Corrections can be raised as an issue on this repository or by
the functional mailbox named on the site's methodology page. A disputed quotation
is hidden while it is reviewed, and the correction log is dated and public.

## Disclaimer

The site is an experimental analysis of statements delivered in the general debate.
It does not represent the views of the President of the General Assembly, the United
Nations or its Member States. Figures come from automated text analysis and may
contain errors. Machine translations and transcripts of interpretation are not
official texts; the official record is the verbatim record of the General Assembly.
