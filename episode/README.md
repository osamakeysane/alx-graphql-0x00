# Task 2: Get a Specific Episode by ID

## Objective

The goal of this task is to write GraphQL queries that retrieve details of specific episodes using their unique ID.

## Endpoint

**https://rickandmortyapi.com/graphql**

## Description

Each query uses the `episode(id: ID!)` field to fetch details about a specific episode.  
The selected fields are:

- `id`
- `name`
- `air_date`
- `episode`

## Files Included

- `episode-id-1.graphql` → Query for episode with ID 1
- `episode-id-1-output.json` → JSON output for episode 1
- `episode-id-2.graphql` → Query for episode with ID 2
- `episode-id-2-output.json` → JSON output for episode 2
- `episode-id-3.graphql` → Query for episode with ID 3
- `episode-id-3-output.json` → JSON output for episode 3
- `episode-id-4.graphql` → Query for episode with ID 4
- `episode-id-4-output.json` → JSON output for episode 4

## Example Query

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
