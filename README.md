# Git Recipes


## Commit contains in a branch
`git branch --contains={commit-hash}`

## What are the commits in branch1 and not in branch2
`git log branch2..branch1`

## What are the commits in branch1 and branch2 after they diverge
`git log branch2...branch1`
`git log branch1...branch2`
