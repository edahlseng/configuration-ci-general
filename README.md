General Continuous Integration Configuration
--------------------------------------------

A [CircleCI Orb](https://circleci.com/docs/2.0/orb-intro/#section=configuration) with general purpose continuous integration configuration.

Getting Started
---------------

Reference the orb within a CircleCI configuration file:

```yaml
version: 2.1

orbs:
  general: edahlseng/general@X.Y.Z
```

See the releases tab for the latest published version number.

Documentation
-------------

Full documentation for this orb can be found in the CircleCI Orbs Registry: [edahlseng/general documentation](https://circleci.com/orbs/registry/orb/edahlseng/general).

Motivation
----------

There are different "chunks" of configuration in this orb, each with a different motivation, described below.

### State

It can be a helpful abstraction to think of jobs and commands as functions that transform some _input_ state to some _output_ state. A workflow then becomes a composition of these different functions. While this abstraction doesn't always fit 100% (many jobs produce effects that break this _input ⟶ output_ model) it can help lead to more deterministic and understandable workflows.

In CircleCI, a workflow's _workspace_, _test results_, and _artifacts_ can be thought of as the different components of state that a given job or command may accept as an input or produce as an output. A collection of commands in this orb simplify the process of dealing with this state:
* get-workspace
* put-all
* put-directory
* put-test-results

_This concept of state was inspired by Concourse tasks and the state monad._

### Release Process

The best release process is one that is automated, removing the barrier to releasing quickly and often. A collection of jobs and commands in this orb automate the release process across a variety of different project types:
* Commands
  * halt-if-not-release-commit
  * halt-if-release-commit
  * setup-git-user
  * tag
* Jobs
  * create-release-pr
  * publish-circleci-dev
  * tag-and-publish-circleci
  * tag-and-publish-npm

### Miscellaneous Configuration

Many projects share similar workflows related to linting, building, running tests, etc. The rest of this orb contains configuration aimed at reducing the boilerplate needed when running these common steps across different projects. Note that this configuration is very opinionated, reflecting the way that my other projects are set up. See the [full documentation for this orb](https://circleci.com/orbs/registry/orb/edahlseng/general) for more information on this miscellaneous configuration.
