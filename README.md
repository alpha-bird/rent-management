# Renting App

- `react-rent-management` - Renting Management Frontend built in React.js
- `react-management-api` - Backend Server for Renting Management built in Node.js/Express

# How to run the project?

Tips: please use node v12.x (prefer to use `v12.22.12`)

## rent-management-api

1. Install MongoDB server on your local
https://www.mongodb.com/try/download/community

2. Install npm packages
- Go to the backend service directory : `cd /rent-management-api`
- `npm install` or `npm install --legacy-peer-deps`

3. Create `.env`
- Add `DB_URI`, `PORT` variable into `.env`

4. Run the service
- `npm run dev` or `npm run start-prod`

## react-rent-management

1. Install npm packages
- Go to the frontend directory : `cd /react-rent-management`
- `npm install` or `npm install --legacy-peer-deps`

2. Run the project
- `npm run start-dev`
