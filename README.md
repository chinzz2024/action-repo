# Action Repo

This repository is used to trigger webhooks for the **[Webhook Monitor project](https://github.com/your-username/webhook-repo)**.

### Test Commands

Run these in your terminal to test the system.

**1. Test PUSH:**
```bash
git checkout -b my-test-branch
echo "test" >> README.md
git add .
git commit -m "test push"
git push origin my-test-branch
```

**2. Test PULL REQUEST:**
Go to this repo on GitHub and create a pull request from `my-test-branch` to `main`.

**3. Test MERGE:**
On the GitHub pull request page, click the "Merge pull request" button.
