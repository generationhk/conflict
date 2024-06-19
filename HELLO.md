0. Fork, clone to own repo first

1. Change code in org
2. Change code in local at same location as above
3. Git add, commit, push code to own account
4. Try to create pull request and fail to merge automatically
5. `git remote add upstream YOUR_ORG_SSH_KEY`
6. Pull org code with `git pull upstream main`
7. Resolve conflict
   - choose any of current/incoming/both
   - `git add .`
   - `git rebase --continue`
8. Push to own repo
9. Create pull request
10. Merge pull request
