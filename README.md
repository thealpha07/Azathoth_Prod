This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
=======
### 2. Write and Test Locally
The feature  is codded and Tested on the local development server (e.g., at http://localhost:3000).

### 3. Push to GitHub
Once satisfied with the local tests, push the bug/feature branch up to the remote GitHub repository.

### 4. Merge to Staging (QA)
Open GitHub and create a Pull Request (PR) to merge your bug/feature branch into the staging branch. Review the changes and click Merge.

### 5. QA Verification
Vercel automatically detects the merge and updates the private Staging environment. Open the Staging URL on multiple devices (phone, laptop) to verify the form works in a real cloud environment connected to the Staging database.

### 6. Merge to Production (UAT to Live)
Once we have verified the feature works perfectly in Staging, open a final Pull Request to merge the staging branch into the main branch.

### 7. Deployment
Click Merge. Vercel instantly detects the update on the main branch and deploys the finalized code to the live public domain.
