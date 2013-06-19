

Update author email and committer email for all commits in a repo
```
git filter-branch --env-filter "GIT_AUTHOR_EMAIL='mail@gmail.com'; GIT_COMMITTER_EMAIL='mail@gmail.com' " HEAD
```                                                                                                                               
