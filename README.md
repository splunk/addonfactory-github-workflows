# addonfactory-github-workflows

This repository contains workflows that can be reused in Github actions.

# explicitly configure permissions when using reusable-agreements, in case your GITHUB_TOKEN workflow permissions are set to read-only in repository settings
permissions:
  actions: write
  contents: write
  pull-requests: write
  statuses: write
