<!-- markdownlint-disable -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| command | Command to run tests | N/A | true |
| docker-compose-version | Docker compose version | 1.29.2 | false |
| entrypoint | Entrypoint | /bin/sh | false |
| file | Docker compose file | N/A | true |
| login | Docker login |  | false |
| password | Docker password |  | false |
| registry | Docker registry | N/A | true |
| service | Service run tests inside | N/A | true |
| workdir | Working directory | ./ | false |

## Outputs

| Name | Description |
|------|-------------|
<!-- markdownlint-restore -->
