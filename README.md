# reusable-workflow-poc
POC for a reusable Github Action Workflow.

This repo contains a GH actions workflow script that can be called from another repositories GH actions workflow.

This separate repository workflow script: https://github.com/chetwoodfinancial/call-reusable-workflow-poc/blob/master/.github/workflows/call-test-workflow.yaml
calls this one and passes in the `app-name` variable which is flagged as required.
