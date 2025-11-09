# Matrix Build Demo

This repository demonstrates GitHub Actions matrix builds with artifact management.

## Features
- Parallel builds for multiple Node.js versions (14.x, 16.x, 18.x)
- Automatic artifact generation and upload
- Build information tracking

## Contact
your.email@example.com

## Workflow
The GitHub Actions workflow in `.github/workflows/matrix-build.yml` runs on:
- Push to main branch
- Pull requests to main branch
- Manual workflow dispatch

Each job generates unique build artifacts with metadata.
```

**⚠️ IMPORTANT: Replace `your.email@example.com` with your actual email address**

4. Click **"Commit changes"**
5. Type message: `Add README`
6. Click **"Commit directly to the main branch"**

---

## Step 3: Check if Workflow is Running

1. Go to your repo: `https://github.com/yourusername/demo`
2. Click the **"Actions"** tab (top menu)
3. You should see **"Matrix Build with Artifacts"** workflow

**Wait 1-2 minutes for it to complete** (you'll see checkmarks ✅)

---

## Step 4: Verify Artifacts

1. In the **Actions** tab, click on the workflow run
2. Scroll down to find **"Artifacts"** section
3. You should see **3 artifacts:**
   - `build-42df3f9-node14.x`
   - `build-42df3f9-node16.x`
   - `build-42df3f9-node18.x`

---

## Step 5: Submit Your Answer

Once you see all 3 artifacts, submit:

**Your Repository URL:**
```
https://github.com/yourusername/demo
