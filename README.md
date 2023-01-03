# Circle CI Newman experiment

This project is an experiment of a simple CI/CD pipeline with [CircleCI](https://circleci.com) by running
[Newman](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman) CLI
with a bunch of APIs. The Newman report is generated with html extra
[plugin](https://www.npmjs.com/package/newman-reporter-htmlextra) (see `newman-report-examples`)

# Conventions

Git commit message convention

```
Format:
<type>(<scope>): <subject>

Type	Description
style	Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
chore	Changes to the build process or auxiliary tools and libraries such as documentation generation
docs	Documentation Updates
feat	New Features
fix	Bug Fixes
refactor	Code Refactoring
test	Adding missing tests
perf	A code change that improves performance
```