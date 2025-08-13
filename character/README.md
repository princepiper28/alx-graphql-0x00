# Character Queries — alx-graphql-0x00

This directory contains GraphQL queries to fetch specific characters by ID using the Rick and Morty GraphQL API.

## Files

- `character-id-1.graphql`: Query for character with ID 1  
- `character-id-1-output.json`: Output JSON from the query  
- `character-id-2.graphql`: Query for character with ID 2  
- `character-id-2-output.json`: Output JSON from the query  
- `character-id-3.graphql`: Query for character with ID 3  
- `character-id-3-output.json`: Output JSON from the query  
- `character-id-4.graphql`: Query for character with ID 4  
- `character-id-4-output.json`: Output JSON from the query

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