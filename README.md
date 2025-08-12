# GraphQL Character Query by ID

## Objective
Learners will write a GraphQL query to retrieve a specific character’s information using their ID.

## Endpoint
Use the following GraphQL endpoint:  

## Instructions
- Write a GraphQL query using the `character(id: ID!)` field to fetch the details of a character.
- Use IDs: **1**, **2**, **3**, **4**.
- Include the following fields in your query:
  - `id`
  - `name`
  - `status`
  - `species`
  - `type`
  - `gender`
- Save each query in separate `.graphql` files:
  - `character-id-1.graphql`
  - `character-id-2.graphql`
  - `character-id-3.graphql`
  - `character-id-4.graphql`
- Save the results in corresponding `.json` files:
  - `character-id-1-output.json`
  - `character-id-2-output.json`
  - `character-id-3-output.json`
  - `character-id-4-output.json`

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
