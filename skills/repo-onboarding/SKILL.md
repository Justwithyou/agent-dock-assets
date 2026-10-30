---
apiVersion: adock/v1alpha1
kind: skill
id: repo-onboarding
title: Repository Onboarding
description: Learn the structure and conventions of a repository.
owners: [team]
labels: [onboarding]
spec:
  triggers: [new repository]
  dependencies: []
  entrypoint: scripts/collect.sh
---
Read references/start-here.md and inspect the repository before making changes.
