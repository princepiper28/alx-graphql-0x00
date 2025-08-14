# Character Queries — alx-graphql-0x00

This directory contains GraphQL queries to fetch specific characters by ID using the Rick and Morty GraphQL API.

## Files

- `characters-id-1.graphql`: Query for character with ID 1  
- `characters-id-1-output.json`: Output JSON from the query  
- `characters-id-2.graphql`: Query for character with ID 2  
- `characters-id-2-output.json`: Output JSON from the query  
- `characters-id-3.graphql`: Query for character with ID 3  
- `characters-id-3-output.json`: Output JSON from the query  
- `characters-id-4.graphql`: Query for character with ID 4  
- `characters-id-4-output.json`: Output JSON from the query

## Usage

Each `.graphql` file contains the following query structure:

```graphql
query {
  character(id: <ID>) {
    id
    name
    status
    species
    type
    gender
  }
}

# Episode Queries — alx-graphql-0x00

This directory contains GraphQL queries to fetch specific episodes by ID using the Rick and Morty GraphQL API.

## Files

- `episode-page-1.graphql`: Query for episode with ID 1  
- `characters-page-1-output.json`: Output JSON from the query for episode 1  
- `characters-page-2.graphql`: Query for episode with ID 2  
- `characters-page-2-output.json`: Output JSON from the query for episode 2  
- `characters-page-3.graphql`: Query for episode with ID 3  
- `characters-page-3-output.json`: Output JSON from the query for episode 3  
- `characters-page-4.graphql`: Query for episode with ID 4  
- `characters-page-4-output.json`: Output JSON from the query for episode 4  

## Usage

Each `.graphql` file contains the following query structure:

```graphql
query {
  episode(id: <ID>) {
    id
    name
    air_date
    episode
  }
}