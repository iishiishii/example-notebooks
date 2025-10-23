---
title: "Notebook Test Job failure - {{ env.GITHUB_WORKFLOW }}"
assignees:
  - iishiishii
labels:
  - bug
---

## JupyterHub Notebook Testing Job Failure

**Server:** {{ env.SERVER_NAME }}
**Server URL:** {{ env.SERVER_URL }}
**Workflow:** {{ env.GITHUB_WORKFLOW }}
**Run ID:** {{ env.GITHUB_RUN_ID }}

### Failed Workflow Details
- **Workflow URL:** {{ env.GITHUB_SERVER_URL }}/{{ env.GITHUB_REPOSITORY }}/actions/runs/{{ env.GITHUB_RUN_ID }}
- **Repository:** {{ env.GITHUB_REPOSITORY }}
- **Server Name:** {{ env.SERVER_NAME }}
- **Server URL:** {{ env.SERVER_URL }}
- **Date:** {{ date | date('YYYY-MM-DD HH:mm:ss UTC') }}
- **Notebook Execution Status:** {{ env.NOTEBOOK_SUCCESS }}
- **Success Patterns Found:** {{ env.PATTERNS_FOUND }}/8

### Description

- The notebook execution test has failed for the **{{ env.SERVER_NAME }}**.

### Additional Info
- The failure occurred during automated testing of notebook functionality {{ env.NOTEBOOK_NAME }}
- Error found during testing: {{ env.ERROR_FOUND }}