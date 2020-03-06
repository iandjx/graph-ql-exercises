GraphQL Exercises

Backend Setup

1. Create Heroku app
2. Install Heroku Postgres
3. Install PGAdmin
4. Install Docker

CLI Commands

1. `npm install -g prisma`
2. `prisma init prisma`
3. `docker-compose up -d`
4. `prisma deploy`
5. `npm run get-schema`

Deploying to dev and prod

1. dev - `prisma deploy -e ../config/dev.env`
1. prod
   a. `prisma login`
   b. `prisma deploy -e ../config/prod.env`
