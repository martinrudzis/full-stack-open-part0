```mermaid
sequenceDiagram
Browser->>Server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
Server-->>Browser: HTTP 201 response (note created)
```