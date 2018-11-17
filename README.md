Continuous Integration Configuration
------------------------------------

Currently CircleCI configuration.

```shell
circleci orb validate sources/general.yml
circleci orb publish sources/general.yml edahlseng/general@dev:staging
circleci orb publish promote edahlseng/general@dev:staging major|minor|patch
```
