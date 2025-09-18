# MC-contact

## Prerequisite
```bash
git config --global alias.mr '!sh -c '\''git fetch $1 merge-requests/$2/head:mr-$1-$2 && git checkout mr-$1-$2'\'' -'
```

## Work
```bash
git clone ssh://git@gitlab.cern.ch:7999/cms-exo-mci/EXO-MCsampleRequests.git
git mr origin $PR_ID
```

## Referece
- [restapi](https://cms-pdmv-prod.web.cern.ch/mcm/restapi)
- [mcm_scripts](https://github.com/cms-PdmV/mcm_scripts)