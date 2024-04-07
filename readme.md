# Nivesh - Financial Literacy

## Introduction
A website that provides information on financial literacy. It provides information on various topics such as budgeting, saving, investing, and retirement planning. The website also provides resources such as articles, videos, and tools to help users improve their financial literacy.

## Features
- Articles: The website provides articles on various financial topics to help users learn more about personal finance.
- Videos: The website provides videos on various financial topics to help users learn more about personal finance.
- Tools: The website provides tools such as calculators and budgeting templates to help users manage their finances.
- Resources: The website provides links to other websites and resources that can help users improve their financial literacy.
- Paper Trading: The website provides a paper trading platform where users can practice trading stocks without using real money.
- Forums: The website provides forums where users can ask questions and discuss financial topics with other users.

## Technologies
- React
- Node.js
- Express
- PostgreSQL
- Supabase

## Setup
1. Clone the repository
```
https://github.com/bashlogs/Financial-Literacy.git
```

2. Install the dependencies
```
# Install dependencies for backend, frontend, and stock
npm install
```

3. Database setup
```
Rename the .env.example file to .env and add your Supabase URL and Supabase Key

DB_USER=
DB_HOST=
DB_DATABASE=
DB_PASSWORD=
DB_PORT=

Add the following to the .env file
```

4. Prisma setup
```
npx prisma db push
```

5. Run Frontend
```
npm start
```

6. Run Backend
```
npm run dev
```

7. Open Live Server of Stock
```
Open the live server on port 5500
Ex. http://127.0.0.1:5500/Stock/index.html
```
