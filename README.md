# GraphQLLearnings
graphQLLearnigs



npm install

npm run devStart

go to browser:

{
  books{
    name
    id
  }
}

{
  authors{
  name,authorId
  }
}

{
  book(id:1){
    name
  }
}

{
  author(id:1){
    name
    id
  }
}




Mutation example:

mutation{
  addBook(
    name:"preetham", authorId:1
  ) {
    name
  }
  
}
