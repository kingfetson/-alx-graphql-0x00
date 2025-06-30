# GraphQL Character Query Project

This directory contains GraphQL queries and their respective outputs for characters with IDs 1 through 4 using the `character(id: ID!)` field.

## Queries

Each `.graphql` file contains a query to fetch the following fields:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Structure

- `character-id-1.graphql` → Query for character ID 1
- `character-id-1-output.json` → API response for character ID 1
- ...

## Example

### Query

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

Response:
{
  "data": {
    "character": {
      "id": "1",
      "name": "Rick Sanchez",
      "status": "Alive",
      "species": "Human",
      "type": "",
      "gender": "Male"
    }
  }
}


---

## 🐙 Step 4: Initialize Git

Make sure you're still in the `character` directory:

```bash
git init
git add .
git commit -m "Add GraphQL queries and responses for characters 1–4"
☁️ Step 5: Create GitHub Repo (if not done yet)
Go to GitHub and create a new repo named: alx-graphql-0x00

Don't initialize with README or .gitignore — you've already created them.

🔗 Step 6: Link GitHub Remote and Push
Back in your terminal:
git remote add origin https://github.com/kingfetson/alx-graphql-0x00.git
git branch -M main
git push -u origin main
Replace your-username with your actual GitHub username.