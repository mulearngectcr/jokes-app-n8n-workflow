## Joke Generator Workflow

A simple n8n automation workflow that fetches a random joke from the Official Joke API and sends it as a formatted email using Gmail.

### Workflow

```text
Manual Trigger
      ↓
HTTP Request (Random Joke API)
      ↓
Gmail (Send Email)
```

### Features

* Fetches a random joke from a public API
* Extracts joke setup and punchline
* Sends a styled HTML email
* Uses Gmail OAuth2 authentication

### Technologies Used

* n8n
* Gmail OAuth2
* Official Joke API

### Usage

1. Configure Gmail OAuth2 credentials.
2. Execute the workflow.
3. Receive a random joke via email.


