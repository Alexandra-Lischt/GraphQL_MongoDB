# GraphQL_MongoDB

## Install

    yarn

## Developing

<b> • Defining a GraphQL schema</b><br/><br/>
A GraphQL schema is at the core of any GraphQL server implementation. It describes the functionality available to the client applications that connect to it.

![SFVSDFSF](https://user-images.githubusercontent.com/49699293/69745111-54f21b80-1120-11ea-9c90-5893998fc58d.png)<br/>
schema.graphql

<b> • Defining a Mongoose schema</b><br/><br/>
Everything in Mongoose starts with a Schema. Each schema maps to a MongoDB collection and defines the shape of the documents within that collection.

![sdfsdf](https://user-images.githubusercontent.com/49699293/69745217-8cf95e80-1120-11ea-9dc5-8e371ba28d59.png)</br>
User.js

<b> • Defining resolvers</b><br/><br/>
A resolver is a function that resolves a value for a type or field in a schema.

![bsgsgsg](https://user-images.githubusercontent.com/49699293/69745411-e95c7e00-1120-11ea-99bd-80351acfde45.png)</br>
resolvers.js

Then you can run:

    node src/server.js

## URL

    localhost:4000
