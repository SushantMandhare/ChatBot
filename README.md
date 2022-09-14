# ChatBot
GCP Chat Bot

Create a project with the Google Cloud Console, and enable the Dialogflow API.

Set up authentication. For example, from the Cloud Console, create a service account, download its json credentials file, then set the appropriate environment variable:

set GOOGLE_APPLICATION_CREDENTIALS=/path/to/your-project-credentials.json
In our project the json are in src/main/resources

To run tests, set GOOGLE_CLOUD_PROJECT to your PROJECT_ID:

set GOOGLE_CLOUD_PROJECT=PROJECT_ID
