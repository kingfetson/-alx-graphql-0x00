# GraphQL Episode Query

This project contains a GraphQL query that fetches a specific episode by ID using the `episode(id: ID!)` field from the Rick and Morty API.

### Query Fields:
- `id`
- `name`
- `air_date`
- `episode`

Additional files include paginated character queries and their JSON responses for further exploration.
# GraphQL Episode Query

This project contains a GraphQL query that fetches a specific episode by ID using the `episode(id: ID!)` field from the Rick and Morty API.

### Query Fields:
- `id`
- `name`
- `air_date`
- `episode`

Additional files include paginated character queries and their JSON responses for further exploration.
# GraphQL Episode Query

This project contains a GraphQL query that fetches a specific episode by ID using the `episode(id: ID!)` field from the Rick and Morty API.

### Query Fields:
- `id`
- `name`
- `air_date`
- `episode`

Additional files include paginated character queries and their JSON responses for further exploration.
🔹 3. Optional Bonus Files (Add if needed)
If you want to simulate paginated character queries:

✅ characters-page-1.graphql
query {
  characters(page: 1) {
    info {
      count
      pages
      next
      prev
    }
    results {
      id
      name
    }
  }
}
Create 3 more files (characters-page-2.graphql, characters-page-3.graphql, characters-page-4.graphql) and change the page: X value accordingly.

For their outputs, copy sample responses or use Postman or GraphQL Playground and paste the results into characters-page-X-output.json.

✅ Final Step: Commit and Push
From your root project folder:
cd C:\Users\zak\Documents\alx-graphql-0x00

git add episode
git commit -m "Add episode query and paginated character queries"
git push origin main
