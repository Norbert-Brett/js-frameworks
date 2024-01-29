---
sidebar_position: 2
---

# React

React is a JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

## Prerequisites

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [React](https://reactjs.org/)

## Getting Started (old way)

To get started with React, you need to install the React CLI. You can do this by running the following command:

```bash
npm install -g create-react-app
```

This will install the React CLI globally on your machine. You can now create a new React project by running the following command:

```bash
create-react-app my-app
```

This will create a new React project called `my-app`. You can now run the project by running the following command:

```bash
cd my-app
npm start
```

This will start the development server on port `3000`. You can now open your browser and navigate to `http://localhost:3000` to see your application running.

## Getting Started (new way)

The new React docs recommend using a production-grade React framework that has a server-side rendering solution.

### Next.js

Next.js is a full-stack React framework. It’s versatile and lets you create React apps of any size—from a mostly static blog to a complex dynamic application. To create a new Next.js project, run in your terminal:

```bash
npx create-next-app@latest
```

### Remix

Remix is a full-stack React framework with nested routing. It lets you break your app into nested parts that can load data in parallel and refresh in response to the user actions. To create a new Remix project, run:

```bash
npx create-remix
```

### Gatsby

Gatsby is a React framework for fast CMS-backed websites. Its rich plugin ecosystem and its GraphQL data layer simplify integrating content, APIs, and services into one website. To create a new Gatsby project, run:

```bash
npx create-gatsby
```

## Resources

- [React](https://react.dev/)
- [React CLI](https://reactjs.org/docs/create-a-new-react-app.html)
- [Next.js](https://nextjs.org/)
- [Remix](https://remix.run/)
- [Gatsby](https://www.gatsbyjs.com/)