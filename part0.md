Browser->>+Server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
activate Server
Server-->>-Browser: document
deactivate Server
Browser->>+Server: GET https://studies.cs.helsinki.fi/exampleapp/notes
activate Server
Server-->>-Browser: document
deactivate Server
Browser->>+Server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
activate Server
Server-->>-Browser: CSS File
deactivate Server
Browser->>+Server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
activate Server
Server-->>-Browser: Javascript File
deactivate Server
Browser->>+Server:GET https://studies.cs.helsinki.fi/exampleapp/data.json
activate Server
Server-->>-Browser: JSON File
deactivate Server

![diagramcase](https://github.com/paulohsousa/FullstackOpen/assets/20420330/5da926a3-10de-42df-a4fb-a91d109e8ce3)
