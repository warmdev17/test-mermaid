# test-mermaid
```mermaid
erDiagram
    USER {
        int id PK
        string name
        string email
    }

    PROBLEM {
        int id PK
        string title
    }

    SUBMISSION {
        int id PK
        int userId FK
        int problemId FK
        string status
    }

    USER ||--o{ SUBMISSION : submits
    PROBLEM ||--o{ SUBMISSION : has
