# react-context Bad vs. Good Implementation
Why I Never Use React Context!? It's all because of how Context works by passing down props to every single child. And when a single state value gets updated the whole children tree gets re-rendered. Fortunately, there is a fix for it!
Consume your context with a custom hook, not with useContext...

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
