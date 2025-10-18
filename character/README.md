# Task 0 - Get a Specific Character by ID

This folder contains GraphQL queries and outputs for retrieving specific characters
from the Rick and Morty GraphQL API.

Files:

- character-id-1.graphql -> Query for character with id = 1
- character-id-1-output.json -> API response for id = 1
- character-id-2.graphql -> Query for character with id = 2
- character-id-2-output.json -> API response for id = 2
- character-id-3.graphql -> Query for character with id = 3
- character-id-3-output.json -> API response for id = 3
- character-id-4.graphql -> Query for character with id = 4
- character-id-4-output.json -> API response for id = 4

Each .graphql file uses this query:

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
```
