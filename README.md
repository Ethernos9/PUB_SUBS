# 📚 Basic Pub/Sub App

This project demonstrates a simple Publish/Subscribe pattern using Redis and a Singleton class in Node.js.

## 🛠️ Prerequisites

- Ensure you have [Docker](https://www.docker.com/products/docker-desktop) installed on your system.
- Install [Node.js](https://nodejs.org/) (LTS version recommended).

## 🚀 Getting Started

### Step 1: Setup Redis

1. Run the following command to start Redis using Docker:

   \`\`\`bash
   docker run -d -p 6379:6379 redis
   \`\`\`

2. Access the Redis container:

   \`\`\`bash
   docker exec -it <container_id> /bin/bash
   \`\`\`

3. Open Redis CLI:

   \`\`\`bash
   redis-cli
   \`\`\`

### Step 2: Run the Application

1. Install the necessary dependencies:

   \`\`\`bash
   npm install
   \`\`\`

2. Start the application:

   \`\`\`bash
   npm run dev
   \`\`\`

## 📄 Features

- Implements basic Publish/Subscribe (Pub/Sub) pattern using Redis.
- Uses a Singleton class to manage connections.

## 📦 Tech Stack

- **Node.js**: Server-side JavaScript runtime.
- **Redis**: In-memory data structure store, used as a## BASIC PUB_SUB APP
  # it uses concept of redis , singelton Class

## Commands to setup Redis 
  docker run -d -p 6379:6379 redis
  docker exec -it container_id /bin/bash
  redis-cli

## Commands to Run App
npm install
npm run dev
 
