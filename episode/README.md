# Episode Queries — alx-graphql-0x00

This directory contains GraphQL queries to fetch specific episodes by ID using the Rick and Morty GraphQL API.

## Files

- `episode-page-1.graphql`: Query for episode with ID 1  
- `characters-page-1-output.json`: Output JSON for episode with ID 1  
- `characters-page-2.graphql`: Query for episode with ID 2  
- `characters-page-2-output.json`: Output JSON for episode with ID 2  
- `characters-page-3.graphql`: Query for episode with ID 3  
- `characters-page-3-output.json`: Output JSON for episode with ID 3  
- `characters-page-4.graphql`: Query for episode with ID 4  
- `characters-page-4-output.json`: Output JSON for episode with ID 4  

## Query Structure

```graphql
query {
  episode(id: <ID>) {
    id
    name
    air_date
    episode
  }
}