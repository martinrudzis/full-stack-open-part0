```mermaid
sequenceDiagram
Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/spa
Server-->>Browser: HTML for single page notes 
Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
Server-->>Browser: CSS styling sheet for the webpage
Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/spa.js
Server-->>Browser: JavaScript file for the webpage
Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
Server-->Browser: JSON file containing the data for the page 
```