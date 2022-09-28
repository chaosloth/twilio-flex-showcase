# Serverless Showcase

Showcase a set of things using Twilio Serverless + Airtable as a backend and NextJS + Twilio Paste as the frontend

# Configuration

1. Create an Airtable account
2. Get the API key for your base
3. Configure the `.env` file with your variables

# Deployment

1. Build the next project with `build:next`, this will populate the `serverless/dist/assets` folder
2. Open a terminal in the `<project>/serverless` directory
3. Deploy the serverless project with `twilio serverless:deploy`
