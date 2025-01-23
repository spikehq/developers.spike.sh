# Introduction

The API v1.1.0 is in beta, we would highly appreciate your feedback, write to us at developers@spike.sh. Find your API key on this page.

Our API is fairly straightforward. Some important points you should read

Users, Escalations, Incidents, Services, Integrations, and On-call schedules belong to a team. To fetch or create anything, a valid Team ID is needed in the header.
x-api-key is required in headers for all routes while x-team-id is for most but not all routes
We do not support archiving from the API yet
For user specific operations, you can fetch user Ids from org routes and use them. A User ID is required in query parameters for routes such as getting upcoming shifts for a user
