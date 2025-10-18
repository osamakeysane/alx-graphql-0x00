# Task 1: Get a List of All Characters

## Objective

The goal of this task is to write GraphQL queries that retrieve a **paginated list of characters** from the Rick and Morty GraphQL API.

## Endpoint

**https://rickandmortyapi.com/graphql**

## Description

This task uses the `characters(page: Int)` field to fetch a list of characters.  
Each query retrieves one page of characters with selected fields:

- `id`
- `name`
- `status`
- `image`

## Files Included

- `characters-page-1.graphql` → Query for page 1
- `characters-page-1-output.json` → JSON output for page 1
- `characters-page-2.graphql` → Query for page 2
- `characters-page-2-output.json` → JSON output for page 2
- `characters-page-3.graphql` → Query for page 3
- `characters-page-3-output.json` → JSON output for page 3
- `characters-page-4.graphql` → Query for page 4
- `characters-page-4-output.json` → JSON output for page 4

## Example Query

```graphql
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
```
