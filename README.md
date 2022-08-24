This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, clone the repository and cd into the project root directory

Then run the development server:

In a terminal, run any npm or yarn commands below

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Sanity-Backend

From the root directory, cd into the sanity-backend directory and run the command
- `sanity start`

### Environmental varialbles
In order for this application to work as expected, you need to create a file `.env.development` and copy the contents of the `.sample_env.development`
Also replace the necessary keys with the appropriate variable

- NEXT_PUBLIC_SANITY_TOKEN: to be generated from the sanity-backend API settings
- NEXT_SANITY_PROJECT_ID: to be copied from the sanity-backend app
- NEXT_PUBLIC_GOOGLE_API_TOKEN: to be gotten from google cloud by creating an OAuth client ID credential 

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
