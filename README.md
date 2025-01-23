# Introduction  

For questions, reach out to us at [developers@spike.sh](mailto:developers@spike.sh).  
You can find your **API key** on [this page](https://app.spike.sh/api).

## Key Points  

- **Team-Based Scoping**:  
  Users, Escalations, Incidents, Services, Integrations, and On-call schedules are scoped to a **team**.  
  A valid **Team ID** (`x-team-id`) is required in the header for most requests.  

- **Authentication**:  
  Every API request must include an **API key** (`x-api-key`) in the headers.  
  The **Team ID** is required for most, but not all, routes.  

- **User-Specific Operations**:  
  - To perform actions for a user (e.g., fetching upcoming shifts), retrieve **User IDs** from **org routes**.  
  - Some routes require a **User ID** as a query parameter.

- The API does not support **archiving** operations.  
