# SemVer Convention

## Branches

| Branch     | From           | To Branch         | Details                      |
|------------|----------------|-------------------|------------------------------|
| production | master         |        ---        | Production branch            |
| hotfix     | production     | production/master | Hotfix for production branch |
| master     | hotfix/release | production        |                              |
| release    | develop        | master            |                              |
| develop    | master         | feature/bugfix    |                              |
| feature    | develop        | develop           |                              |
| bugfix     | develop        | develop           |                              |
