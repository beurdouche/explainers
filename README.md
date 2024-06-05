# Mozilla Explainers

This document is a work in progress.

This repo is for the development of explainers from Mozilla contributors. 
Mozilla Explainers can start with as little as a sentence summarizing a user-relevant problem 
and how a new technology could help solve it.
The [W3C TAG Explainer](https://tag.w3.org/explainers/) provides a basic outline, examples, and tips for developing explainers.

In general we expect to focus on developing explainers that:
* solve a user-relevant problem as prioritized by the [Mozilla Web Vision](https://www.mozilla.org/en-US/about/webvision/full/) (Web Vision)
* and propose a solution aligned with the Web Vision
* or a counterproposal that is more aligned with the Web Vision than existing technologies or proposals

## How to add an Explainer
1. write up a minimum viable (or more) explainer
2. get reviews and approvals from your senior standards person (ask [@tantek](https://github.com/tantek) for who) and the CTO office (ask [@martinthomson](https://github.com/martinthomson) for who)
3. convert your draft explainer to a name.md (or .html) file and submit a PR to add the file to this repo

## Minimum viable explainer
Start your explainer with at least:

0. short-name (for name.md or .html explainer file)
1. user problem(s) to be solved with a new/improved standard, at least a one sentence description

## Explainer sections
Expand your explainer with the following sections, in order:

2. methodology for approaching & evaluating solutions (e.g. cite & quote from the Web Vision)
3. prior/existing features (if any) and existing proposals (if any) that attempt to solve the problem(s)
4. flaws or limitations in existing features/proposals that prevent solving the problem(s)
5. motivation for this explainer, why we think we can do better than the status quo or other proposals
6. outline of a proposed solution
7. usage, examples, sample code and a prose summary how it clearly solves problem(s)
8. caveats, shortcomings, and other drawbacks of design choices, both current and any prior iterations
9. draft specification
10. incubation and/or standardization destination, this can be:
 * an existing standards-track spec (if any) to incorporate the proposed solution as a feature,
 * an incubation destination (e.g. WICG, WHATWG stage 0, or TC39 stage 0),
 * or a standards working group, e.g. CSS WG (which incubates internally) or a WHATWG work stream if applicable
