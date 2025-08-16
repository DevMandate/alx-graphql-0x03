# ALX Rick and Morty App

This is a Next.js + TypeScript + TailwindCSS + Apollo Client project to interact with the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

## Setup

### 1. Create Project
```bash
npx create-next-app@latest alx-rick-and-morty-app --typescript --eslint --tailwind
```
### 2. Install Dependencies

npm install @apollo/client graphql
npm install --save-dev @types/graphql

### 3. GraphQL Setup
graphql/apolloClient.ts → Apollo Client setup

graphql/queries.ts → Example GraphQL query (Get Episodes)

### 4. Apollo Provider
Updated pages/_app.tsx to wrap the app with ApolloProvider

### 5. Run Dev Server

```npm run dev
Visit http://localhost:3000 in your browser.
```