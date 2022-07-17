# Project Infrastructure is separated into 3 main components

## Database (Postgres)

- The connection to the database exists in udagram-api/src/sequelize.ts
- The database is hosted on AWS RDS

## Backend Server

- The server is build with express, node js, and TypeScript
- The server is hosted on AWS Elastic Beanstalk

## Frontend

- The frontend is built with angular and lives in the udagram-frontend
- The frontend is hosted on AWS S3
