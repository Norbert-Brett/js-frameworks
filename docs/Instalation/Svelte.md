---
sidebar_position: 3
---

# Svelte

Svelte is a free and open-source front end compiler created by Rich Harris. It is used to convert a Svelte component into a highly efficient JavaScript module that surgically updates the DOM. Instead of using techniques like virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.

## Prerequisites

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [Svelte](https://svelte.dev/)

## Getting Started

Svelte recommna using SvelteKit to create a new Svelte project. You can do this by running the following command:

```bash
npm create svelte@latest myapp
```

This will create a new Svelte project called `myapp`. You can now run the project by running the following command:

```bash
cd myapp
npm run dev -- --open
```

This will start the development server on port `3000`. You can now open your browser and navigate to `http://localhost:3000` to see your application running.

### Alternative

If you don't want to use SvelteKit for some reason, you can also use Svelte with Vite (but without SvelteKit)

```bash
npm create vite@latest
```

and then select `svelte` as the framework.

## Resources

- [Svelte](https://svelte.dev/)
- [SvelteKit](https://kit.svelte.dev/)
- [Vite](https://vitejs.dev/)