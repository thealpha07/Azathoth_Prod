# The Merge Order (The Code Pipeline)

### 1. Create the Workspace
Each new issue is developed and treated as an independent fix. Each branch acts as the sandbox for development.

### 2. Write and Test Locally
Write your code and test the feature on your local development server (e.g., at http://localhost:3000).

### 3. Push to GitHub
Once you are satisfied with your local tests, push the feat/contact-form branch up to your remote GitHub repository.

### 4. Merge to Staging (QA)
Open GitHub and create a Pull Request (PR) to merge your feat/contact-form branch into the staging branch. Review the changes and click Merge.

### 5. QA Verification
Vercel automatically detects the merge and updates your private Staging environment. Open your Staging URL on multiple devices (phone, laptop) to verify the form works in a real cloud environment connected to your Staging database.

### 6. Merge to Production (UAT to Live)
Once you have verified the feature works perfectly in Staging, open a final Pull Request to merge the staging branch into the main branch.

### 7. Deployment
Click Merge. Vercel instantly detects the update on the main branch and deploys your finalized code to your live public domain.
