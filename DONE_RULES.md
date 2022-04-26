# Done Rules for Issues 

The done rules define the criteria to meet, before an issue can be moved from doing to done.

Done rules differ for the categories

- [Ops](#ops-issues): Issues related to Kubernetes, Workflows and similar
- [Dev simple](#dev-simple): Simple development issues
- [Dev peer reviewed](#dev-peer-reviewed): Peer reviewed development issues (worth a peer review on each step)
- [Content](#content): Issues related to website content (new pages, texts, videos, ...)

## Ops Issues

Issues related to Kubernetes, Workflows and similar

### Specification
- A specification is done when it is peer reviewed by another DevOps person (does it meets our standards regarding the stack or the k8s cluster?)

### Realization
**common-chart**
- build/deploy without error (github notification, grafana alerts...)


**public-chart**
- on dev (optional): code reviewed by the other DevOps
- on stag (mandatory): build/deploy without error (github notification, grafana alerts...)

### validation
- on stag: new features / upgrades tested successfully by the other DevOps & Requester
- on prod: stag is promoted to prod

## Dev simple

Specification done rules: 

- The developer has no more questions

Implementation done rules: 

- The developer tested locally

Validation done rules: 

- The developer team tested and validated the issue on staging

## Dev peer reviewed

Specification done rules: 

- Developer and requester of the issue validated the spec

Implementation done rules: 

- The developer tested locally
- code reviewed by other dev
- work is visible to the team for reviews (on dev for development issues, on a text for content)

Validation done rules: 

- The developer team tested and validated the issue on staging
- Validated by requester

## Content
