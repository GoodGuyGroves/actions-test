---
title: '{{ env.WORKFLOW }} | {{ date | date("dddd, MMMM Do") }}'
labels: deployment
---
The workflow, `{{ env.WORKFLOW }}`, was just triggered by {{ env.OWNER }}.