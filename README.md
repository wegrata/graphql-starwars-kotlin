### Spark Java + GraphQL + Kotlin
This is a GraphQL server written in Kotlin. The repo contains some data for characters in Star Wars.
It has a schema for this data and defines queries for it. The server uses Spark to expose a POST endpoint
"/graphql". Queries from the client side should be passed to this endpoint.

#### Server

_/graphQL_
  - __query__: GraphQL query to parse.
  - __variables__: any variables for the query.

#### Schema

- __Objects__
  - Human
  - Droid
- __Interfaces__
  - Character
- __Enums__
  - Episode
  - Height

#### Libraries
- [GraphQL Java](https://github.com/graphql-java/graphql-java)
- [GraphKool](https://github.com/beyondeye/graphkool)
- [Spark Java](https://github.com/perwendel/spark)
- [Jackson Kotlin](https://github.com/FasterXML/jackson-module-kotlin)
