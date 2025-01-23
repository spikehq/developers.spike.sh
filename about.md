# About

The API v1.1.0 is in **beta**, we would highly appreciate your feedback, write to us at [developers@spike.sh](mailto:developers@spike.sh). Find your API key on [this page](https://app.spike.sh/api).

Our API is fairly straightforward. Some important points you should read:

1. Users, Escalations, Incidents, Services, Integrations, and On-call schedules belong to a team. To fetch or create anything, a valid Team ID is needed in the header.
2. `x-api-key` is required in headers for all routes while `x-team-id` is for most but not all routes
3. We do not support archiving from the API yet
4. For user specific operations, you can fetch user Ids from org routes and use them. A User ID is required in query parameters for routes such as getting **upcoming shifts** for a user
