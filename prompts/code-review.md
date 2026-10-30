---
apiVersion: adock/v1alpha1
kind: prompt
id: code-review
title: Code Review
description: Review a change for correctness and maintainability.
owners: [team]
labels: [engineering]
spec:
  variables:
    - name: change
      description: Change or diff to review
      required: true
---
Review the following change:

{{change}}
