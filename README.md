# 200ok.vc

## Local Dev

In the root directory of the project:

`cp .env-example .env`

`cp .arc-env-example .arc-env`

`npx sandbox`

## Updating Member Info

Ensure that `.env` has the correct Airtable credentials

`node scripts/sync-airtable.js`