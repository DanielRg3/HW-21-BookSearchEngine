# HomeWork #21 "Book Search Engine"

## About
In this project we will take as starter code a fully functional Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API.

To complete the assignmente we need to :
- Set up anApollo Server to use GraphQl queries and mutations to fetch and modify data, replacing the existing RESTful API.
- Modif the exisitng authentication middleware so that it works in the context of a GraphQL API.
- Create and Apollo Provider so that requests can communicate with an Apollo Server
- Deploy the application in Heroku with a MongoDB using MongoDB Atlas.

## Terminal
npm run develop {to include both the fornt-end and the back-end}

## Content
- apollo packages installed
- Server:
    - serverjs. file to manage the back-end
    - apollo-server-express package
    - schemas with the resolvers and typeDefs
    - routes for the api directions
    - models for the user and books information administration
    - controllers and config connections
- Client/src:
    - App.js to administrate the front end
    - components for the different sections on the webpage
    - pages for the saved books and search books pages

## Learinings
From this project I learned how to switch from RESTful API into GraphQL.
I also reherced how to implement the different packages both inside the Server and Client directories and at the general booksearchengine one.
Finally, it is necessary to update this app through Heroku using the MongoDB Atlas so I reherced this once again.

## Credits
I would like thanks my tutor <cite>Alexis San Javier</cite> for helping me with explenations and walking me through out my mistakes!!!