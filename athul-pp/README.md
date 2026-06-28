# Day 8 Task - Random Joke Generator

This is a manually triggered n8n workflow that fetches a random joke from the Official Joke API and sends it via email.

## Workflow Features
* **Manual Trigger**: Initiates the workflow on demand.
* **HTTP Request**: Fetches a random joke from `https://official-joke-api.appspot.com/random_joke`.
* **IF Node**: Evaluates the joke's length to ensure it meets the minimum character requirement.
* **Send Email**: Delivers the formatted joke (Setup + Punchline) along with a dynamic timestamp.
* **Error Handling**: Enabled "Continue On Fail" for the API request to prevent workflow crashes during fetch errors.