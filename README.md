# test-mermaid
```mermaid
flowchart LR
    USER[User]
    NAME((name))
    EMAIL((email))

    SUBMISSION[Submission]

    USER -->|has| NAME
    USER -->|has| EMAIL
    USER -->|submits| SUBMISSION
