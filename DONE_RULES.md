# Done Rules for Issues 

## DevOps Issues

### Specification
- A specification is done when it is peer reviewed by another DevOps person (does it meets our standards regarding the stack or the k8s cluster?)

### Realization
**common-chart**
- build/deploy without error (github notification, grafana alerts...)


**public-chart**
- on dev (optional): code reviewed by the other DevOps
- on stag (mandatory): build/deploy without error (github notification, grafana alerts...)

### validationon
- on stag: new features / upgrades tested successfully by the other DevOps & Requester
- on prod: stag is promoted to prod



## Minor issue

Specification done rules: 

- The developer has no more questions

Implementation done rules: 

- The developer tested locally

Validation done rules: 

- The developer team tested and validated the issue on staging

## Major Issue

Specification done rules: 

- Developer and requester of the issue validated the spec

Implementation done rules: 

- The developer tested locally
- code reviewed by other dev
- work is visible to the team for reviews (on dev for development issues, on a text for content)

Validation done rules: 

- The developer team tested and validated the issue on staging
- Validated by requester
