# Fix for "Resource not accessible by integration" Error

## What Happened?
Some students who accepted the assignment early got an older version of the grading workflow that tries to post commit comments (which requires special permissions and fails with a 403 error).

## The Good News
**Your score is still being calculated!** The error happens AFTER grading. Check the "Summary" section in the Actions tab to see your score.

## How to Fix It (Optional)

### Option 1: Quick Fix (Just View Your Score)
1. Go to the **Actions** tab in your repo
2. Click on the most recent workflow run
3. Scroll down to the **Summary** section
4. **Your score is there!** Ignore the red error at the bottom.

### Option 2: Update the Workflow (Remove the Error)
If you want to remove the error completely:

1. In your repo, navigate to `.github/workflows/grade.yml`
2. Click the **pencil icon** (Edit this file)
3. Delete everything and paste the updated workflow from the template repo
4. Or run this command in your local repo:

```bash
curl -o .github/workflows/grade.yml https://raw.githubusercontent.com/AppArara/focus-timer-test-template/main/.github/workflows/grade.yml
git add .github/workflows/grade.yml
git commit -m "fix: Update grading workflow to remove 403 error"
git push
```

## Why This Happened
GitHub Classroom creates a snapshot of the template when you accept. Later fixes to the template don't automatically sync to your repo. This is normal GitHub behavior.

## The Technical Details (For Curious Students)
The old workflow tried to post commit comments using `github-script`, but GitHub Classroom repos have restricted permissions (`contents: read` only). The new workflow uses GitHub Actions Summary instead, which doesn't need special permissions.

## Still Having Issues?
Email Dan at: appararahq@gmail.com with:
- Your GitHub username
- A link to your repo
- Screenshot of the error
