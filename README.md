# Overview
This repo contains a centralized Ansible workflow that can be used by other repositories in this organization.

The workflow has two jobs:
1. Ansible Security Scan -- this job runs the [KICS security scanner](https://github.com/marketplace/actions/kics-github-action) against all Ansible files in the repository
2. Ansible Linter -- this job runs the [Ansible Lint](https://github.com/marketplace/actions/run-ansible-lint) tool against all Ansible files in the repository
