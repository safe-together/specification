[![Build Status](https://img.shields.io/travis/safe-together/specification.svg?style=flat-square)](http://travis-ci.org/safe-together/specification)

# SafeTogether Specification

* Editor's Draft: https://safe-together.github.io/specification/
* Latest Published: https://safe-together.github.io/specification/
* Git repository: https://github.com/safe-together/specification
* Working Drafts:
  * Git repository: https://github.com/safe-together/specification (master branch)
* Related web sites:
  * SafeTogether web site: http://safetogether.app/
  * CovidApp - Covid Community Alert: https://coronavirus-outbreak-control.github.io/web/
* Reference implementation source repositories:
  * Contat Tracing app: https://github.com/Coronavirus-Outbreak-Control/
  * Shielding app: *TBD*
  * Quarantine app: *TBD*

This repository contains the source of the SafeTogether Specification
which aims to be a clear, unambiguous, free and implementable documentation for SafeTogether Project.

For the time being, while the migration is in progress, please refer also to the existing draft documents available in reference implementation repositories.

A fair number of spec improvements are currently in the making. If you want to contribute, please refer to a relevant [panel](https://safe-together.github.io/specification/process#panels).


## Editing and building the specification
The specification is built using [Bikeshed](https://tabatkins.github.io/bikeshed/).

Pushing to master triggers the  compliation and publishing in GitHub pages.

## Local building & test
 
If needed, download and install [docker community engine](https://hub.docker.com/search/?type=edition&offering=community)

This command will generated html files in project root, main, stories and process direcories:

```
docker run --rm -t -v ${PWD}:/data  -w /data linkeddatacenter/bikeshed ./build 
```

Note that by default, the generated  .html files will not pushed to repository.
