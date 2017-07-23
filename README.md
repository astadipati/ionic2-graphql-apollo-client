This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

 [GraphQL](http://graphql.org/) It is a sample application integrating Ionic2 with GraphQL using the [Apollo Client for Angular2](http://dev.apollodata.com/angular2/)


## GraphQL Server
I am hosting the server on [Glitch](https://glitch.com) here - [aks-graphql-sample1](https://glitch.com/edit/#!/aks-graphql-sample1?path=README.md:1:0)

Because of CORS issues, I needed to make a modification to my graphQL server to work properly. [See the fix here](https://github.com/apollographql/apollo-client/issues/529#issuecomment-264536745)

## Apollo Client 
- Application shows basic user queries and  mutations
- Controlling the store and UI [using updateQueries](http://dev.apollodata.com/angular2/cache-updates.html#updateQueries) as a more efficient way to update the user interface without requerying the data