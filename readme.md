# Front-end

## Manifest

- **Immutability** - We try to follow Immutable programming approach ✨
- **Purity** - We write pure functions ✍️
- **Readability** - We write readable and reusable code 📘
- **Feedback** - We are open for feedback 📝
- **Learn** - Reviewer and requester should learn from code reviews 🔄
- **Help** - If I get complex task and after 2 hours I don’t have a solution or idea how to solve, I will ask my colleague for help 🤝
- **Interview** - Everybody should be involved in interview process of potential new colleagues 👥
- **Fun** - We here to learn and have fun 🎓🎉

## Tech stack

### ⚠️⚠️⚠️ TypeScript all the way ⚠️⚠️⚠️

Our main building base is [NextJS](https://nextjs.org/docs) deployed to [Vercel](https://vercel.com/).
Any frontend project that looks more like a static application
should use NextJS. Otherwise, for App-like pages we use React with [Vite](https://vitejs.dev/guide/) bundler.
If project requires monorepo we use [TurboRepo](https://turbo.build/).

For styling and quick prototypes - [TailwindCSS](https://tailwindcss.com/docs/guides/nextjs) + [clsx](https://www.npmjs.com/package/clsx) + tailwind-merge to simplify work with className.
If TailwindCSS is not enough and we need to cover more difficult cases, such as complex styles based on props, we go with [StyledComponents](https://styled-components.com/). But its not siutable with Next14.

Component library that we prefer is [Shadcn/ui](https://ui.shadcn.com/)

State management should be as simple as possible and in most cases React context should be enough.
However, for bigger and complex state we can use [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction),
for crazier state - [XState](https://stately.ai/docs/xstate).

In most cases to fetch data [axios](https://axios-http.com/docs/intro) should be enough, however it's advised to use together with
[TanStack Query](https://tanstack.com/query/latest/docs/react/overview) for communication with backed (REST or GraphQL).

Our choice of CMS is [Prismic](https://prismic.io/)

If you need some form then either [Formik](https://formik.org/) (complex) or [React-Hook-Form](https://www.react-hook-form.com/get-started/) (simple) with [Zod](https://zod.dev/) for validation

## TL;DR

## Base

1. [NextJS 14](https://nextjs.org/docs) or React with [Vite](https://vitejs.dev/guide/)

## Style and Components

1. [TailwindCSS](https://tailwindcss.com/docs/guides/nextjs) + [clsx](https://www.npmjs.com/package/clsx) +  tailwind-merge
2. [Shadcn/ui](https://ui.shadcn.com/) based on [Radix-ui](https://www.radix-ui.com/) when Next14 is used
3. [StyledComponents](https://styled-components.com/)

## Data fetching

1. [Axios](https://axios-http.com/docs/intro) - for simple cases
2. [TanStack Query](https://tanstack.com/query/latest/docs/react/overview) 

## State management
1. React context
2. [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction) - mid-complexity
3. [XState](https://stately.ai/docs/xstate) - complex state

## Forms

1. [Formik](https://formik.org/) (complex) 
2. [React-Hook-Form](https://www.react-hook-form.com/get-started/) (simple) with [Zod](https://zod.dev/) for validation

## CMS
1. [Prismic](https://prismic.io/)




