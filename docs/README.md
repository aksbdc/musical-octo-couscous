```mermaid
gitGraph
    commit
    commit
    branch "create"
    branch "configure"
    checkout "create"
    commit
    commit
    checkout "configure"
    commit
    commit
    checkout main
    merge "create"
    merge "configure"
```