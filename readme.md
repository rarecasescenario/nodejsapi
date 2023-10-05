#Video Source
https://www.youtube.com/watch?v=ggxu2K6u6Nw&list=PLopcHtZ0hJF20vLxAKkCus_NTwwrkCfKy&index=39&ab_channel=GetArrays

#Path
-- NodeJs App
Routes
Controller
Error Handling
Database Configuration
MySQL
Handle HTTP Requests
Handle CORS
SQL Queries
Docker - deployment

#App Setup

1. Create a folder nodejsapi
2. npm init -y
3. tsc --init
4. In tsconfig.json uncomment and change entries:
   "outDir": "./dist"
   "rootDir": "./src"
5. Install dependencies
   npm i cors dotenv express ip mysql2
6. Install type definitions for code completion for Typescript
   npm i -D @types/cors @types/express @types/ip types/mysql2 nodemon ts-node typescript
