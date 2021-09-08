# Requirements
```sh
npm install

```

# Run
```sh
node app.js
```

# Test
- use this on the localhost:3000/graphql
```json
{
  post(id: 1) {
    title
    description
    author {
      name
      age
    }
  },
  posts {
    title
    description
    author {
      name
      age
    }
  }
}
```




