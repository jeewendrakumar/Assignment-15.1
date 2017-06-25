# Assignment-15.1

Write a GraphQL query to fetch Books first 20 records

{
  bookStore {
    books(first: 20) {
      edges {
        cursor
        node {
          id
          title
        }
      }
    }
  }
}
