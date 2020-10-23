# github-runner

GitHub Local Runner

This github-runner is based on [myoung34/docker-github-actions-runner](https://github.com/myoung34/docker-github-actions-runner`)

**Essential Part of the `values.yaml``**
```yaml
gitHubRunner:
  secret:
    # Personal Access Token of a user inside the organization
    ACCESS_TOKEN: ""
  env:
    # If this is set to true, the runner will be available for all repositories inside the organization
    ORG_RUNNER: true
    # GitHub Organization (Team) name
    ORG_NAME: githubOrganization
    # Used Labels
    LABELS: self-hosted, linux
```


