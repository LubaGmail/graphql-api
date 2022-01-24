tut
    https://www.ibrahima-ndaw.com/blog/graphql-api-express-mongodb/

http://localhost:4000/graphq

      mutation {
            createArticle(article: {title: "First", body: "This is my first article"}) {
            title
            body
            createdAt
        }
    }

      {
        articles {
            title
            body
            createdAt
        }
    }

    