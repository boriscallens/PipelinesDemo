# PipelinesDemo

Trying out CI/CD for a unity project.
Using a template Unity project for a bit of substance.

## Workflows
  1. Feature branch: when changes are pushed to a feature branch, a build is triggered that only pushes test results
  2. Main branch
    - run tests
    - when successfull build for all platforms
    - gather artifacts in draft, pre-release build
    - push artifacts to itch.io and steam

## Sources
  - https://game.ci/docs
  - https://github.com/features/actions
  - https://github.com/KikimoraGames/itch-publish
  - https://github.com/marketplace/actions/steam-deploy
  - https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions
