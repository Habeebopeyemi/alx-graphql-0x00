# alx-graphql-0x00

## Character Queries - GraphQL

This project demonstrates how to query specific character details using GraphQL.  
We use the `character(id: ID!)` field to fetch character information from the API.

## Endpoint

```http
https://rickandmortyapi.com/graphql
```

### Instructions

We queried characters with IDs `1, 2, 3, 4` and retrieved the following fields:

- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

Each query is saved in a `.graphql` file, and its result is stored in a corresponding `.json` file.
