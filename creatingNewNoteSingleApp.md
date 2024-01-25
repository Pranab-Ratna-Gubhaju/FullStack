0.6: New note in Single page app diagram
## Create a diagram depicting the situation where the user creates a new note using the single-page version of the app at https://studies.cs.helsinki.fi/exampleapp/spa

```mermaid
    sequenceDiagram
    participant browser
    participant server
   
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: {"message":"note created"}
    deactivate server

```
