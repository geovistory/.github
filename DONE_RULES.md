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
