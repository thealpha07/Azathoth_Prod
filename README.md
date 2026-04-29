# The Merge Order (The Code Pipeline)

### 1. Create the Workspace
Each new issue is developed and treated as an independent fix. Each branch acts as the sandbox for development.

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
