## Parking APP

This is a full-stack monorepo application built with Next.js, NestJS, GraphQL, REST, Prisma, Mui, and Tailwind. The application has four frontend applications:

Customer-facing application
Manager application
Wallet application
Admin application
The application also has two APIs:

GraphQL API
REST API
The application has the following features:

Search for garages
Book parking slots
Request valet drivers
View booking history
Manage bookings
Assign and track valet drivers
Check in and check out vehicles
The application is built using a monorepo architecture, which allows for better code sharing and collaboration between the different teams working on the project. The application is also built using a number of modern technologies, such as Next.js, NestJS, GraphQL, and Prisma, which make it a very powerful and scalable application.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (>= 14.x)
- Yarn (>= 1.22.x)
- Docker
- Git

## Getting Started

### 1. Clone the Repository

Clone the repository to your local machine using Git.

```bash
git clone repo-url
```

### 2. Install Dependencies

Install the project dependencies using Yarn.

```
yarn install
```

### 3. Set Up Environment Variables

Create a .env file in the root directory and add the necessary environment variables. Refer to .env.example for the required variables.

### 4. Run the Database with Docker Compose

Start the PostgreSQL database using Docker Compose.

```
docker-compose up -d
```

### 5. Run Prisma Migrations

After the database is running, apply Prisma migrations to set up the database schema.

```
yarn prisma migrate dev
```

### 6. Run the Applications

You can run the individual applications using the following commands:

#### API Application

Navigate to the apps/api directory and start the API server.

```
cd apps/api
yarn dev
```

#### WEB Applications

Navigate to the apps/web directory and start the WEB server.

```
cd apps/web
yarn dev
```
