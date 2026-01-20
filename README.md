# nest-js-graphql-authentication-with-bycrpt-jst-redis
NestJS Authentication without Passport using GraphQL, Bcrypt, JWT and Redis


# Features -
Register
Login
Show profile
Logout


# Technologies stack:
GraphQL
JWT
Bcrypt
TypeORM + MySQL
Redis
Docker


# Setup
1. Install the required dependencies
$ npm install
2. Rename the .env.example filename to .env and set your local variables
$ mv .env.example .env
3. Start the application
   
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
Docker for development
# start the application
$ npm run docker:up

# stop the application
$ npm run docker:down
