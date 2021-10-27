# SemVer Convention

## Branches

### With Additional Production Branch

![Branch Flow](./draw.io/diagram.png)

| Branch     | From Branch    | To Branch              | Details                      |
|------------|----------------|------------------------|------------------------------|
| production | master         | hot fix                | Production Branch            |
| hotfix     | production     | production/master      | Hotfix for Production Branch |
| master     | hotfix/release | production/develop     | Master Branch                |
| release    | develop        | master                 | New Candidate to Release     |
| develop    | master         | feature/bugfix/release | Develop Branch               |
| feature    | develop        | develop                | Featre Branch                |
| bugfix     | develop        | develop                | Bugfix Bramch                |

## Commits

| Prefix       | Message                                      |
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
