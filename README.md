# Project Name

This repository contains two submodules: `client-side` and `server-side`.

## Getting Started

### 1. Clone the Repository with Submodules

```bash
git clone --recursive [repository-url]
cd [project-name]
```

### 2. Environment Setup

The project requires environment variables to be set up for both the client and server applications.

#### Client-side Environment Setup

1. Navigate to the client-side directory:

   ```bash
   cd client-side
   ```

2. Copy the sample environment file:

   ```bash
   cp .env.sample .env
   ```

3. Create a new `.env` file and add the necessary variables.

4. Paste the variables from the sample environment file into the new `.env` file.

#### Server-side Environment Setup

1. Navigate to the server-side directory:

   ```bash
   cd server-side
   ```

2. Copy the sample environment file:

   ```bash
   cp .env.sample .env
   ```

3. Update the `.env` file with your configuration:

4. Paste the variables from the sample environment file into the new `.env` file.

#### Root Level Environment Setup

1. In the root directory, copy the sample environment file:
   ```bash
   cp .env.sample .env
   ```
2. Update the `.env` file with DB configuration i will provide you:

### 3. Running the Project

After setting up all environment variables, you can build and run the project using Docker Compose:

```bash
docker-compose up --build
```

This command will:

- Build all necessary Docker images
- Create and start the containers
- Set up the network between services
- Start the client, server, and database services

You can access:

- Frontend application at: `http://localhost:3000`
- Backend API at: `http://localhost:3008`

To stop the containers, use either:

```bash
# Stop and remove containers
docker-compose down

# Or press Ctrl + C in the terminal where docker-compose up is running
```
