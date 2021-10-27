# SemVer Convention

## Branches

| Branch     | From           | To Branch         | Details                      |
|------------|----------------|-------------------|------------------------------|
| production | master         |        ---        | Production Branch            |
| hotfix     | production     | production/master | Hotfix for Production Branch |
| master     | hotfix/release | production        | Master Branch                |
| release    | develop        | master            | New Candidate to Release     |
| develop    | master         | feature/bugfix    | Develop Branch               |
| feature    | develop        | develop           | Featre Branch                |
| bugfix     | develop        | develop           | Bugfix Bramch                |

## Commits

| Prefix       | Example                                      |
|--------------|----------------------------------------------|
| feat         | feat: add Kerberos auth to database          |
| fix          | fix: problem auth via Kerberos               |
| style        | style: Kerberos method spacing               |
| docs         | docs: added Kerberos auth documentation      |
| build/vendor | build: updated Kerberos dependency           |
| perf         | perf: increase auth via Kerberos performance |
| test         | test: add test for Kerberos auth             |
| refactor     | refactor: renamed varaibles in Kerberos auth |
| chore        | chore: add Kerberos dependency               |
