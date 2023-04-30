# Notes backend

This is a personal project to manage differents types of notes.

## Prerequisites

- node >=18.x.x
- npm >=9.0.0
- Docker
- Docker-compose

## Step by Step with Docker

1. Copy .env.example to .env

   ```shell
   cp .env.example .env
   ```

2. Start the project with docker-compose!

   ```shell
   docker-compose up -d
   ```

## Services

- **http://localhost:1337** : Notes Backend
- Postgres Database

## Step by Step without Docker

1. Copy .env.example to .env

   ```shell
   cp .env.example .env
   ```

2. Update .env file with yours variables

3. Install packages with npm

   ```shell
   npm install
   ```

4. Run server on develop environment.

   ```shell
   npm run dev
   ```
