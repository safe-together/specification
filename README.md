# SafeTogether Specification

* Editor's Draft: https://safe-together.github.io/specification/
* Latest Published: https://safe-together.github.io/specification/
* Working Drafts:
  * Currently in progress
* Reference implementation repositories:
  * Shielding app: https://github.com/g0v-it/staysafe-shielding
  * Contat Tracing app: *TBD*
  * Quarantine app: *TBD*

This repository contains the source of the SafeTogether Specification
which aims to be a clear, unambiguous, free and implementable documentation for [SafeTogether Project].

For the time being, while the migration is in progress, please refer also to the existing draft documents available in reference implementation repositories.

A fair number of spec improvements are currently in the making. If you want to contribute, please refer to a relevant [panel].


## Editing and building the specification
The specification is built using [Bikeshed](https://tabatkins.github.io/bikeshed/).

Pushing to master triggers the  compliation and publishing in GitHub pages.

## Local building
 
If needed, download and install [docker community engine](https://hub.docker.com/search/?type=edition&offering=community)

For example to generate the html documentation for stories:

```
mkdir distrib
docker run --rm -v ${PWD}:/data linkeddatacenter/bikeshed bikeshed spec /data/stories/index.bs 
```

Note that by default .html files are not pushed to repository
