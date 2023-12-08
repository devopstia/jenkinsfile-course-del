## Condictions
```groovy
BRANCH_NAME == "dev" || BRANCH_NAME == "prod"
BRANCH_NAME == "dev" || BRANCH_NAME == "prod" || BRANCH_NAME == "qa"
BRANCH_NAME == "dev" && BRANCH_NAME == "prod"
BRANCH_NAME == "dev" && BRANCH_NAME == "prod" && BRANCH_NAME == "qa"

BRANCH_NAME != "master" && BRANCH_NAME != "prod"

BRANCH_NAME == "dev" && CODE_CHANGES == true


env.BRANCH_NAME == "dev" || env.BRANCH_NAME == "prod"
env.BRANCH_NAME == "dev" || env.BRANCH_NAME == "prod" || env.BRANCH_NAME == "qa"
env.BRANCH_NAME == "dev" && env.BRANCH_NAME == "prod"
env.BRANCH_NAME == "dev" && env.BRANCH_NAME == "prod" && env.BRANCH_NAME == "qa"

env.BRANCH_NAME != "master" && env.BRANCH_NAME != "prod"

env.BRANCH_NAME == "dev" && env.CODE_CHANGES == true
```