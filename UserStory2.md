User Story 2
============
1. Create a new branch and set upstream
```git
git checkout -b iss2
git push origin iss2
```

2. Changes to branch 'master' and do it.
```git
git checkout master
```

3. Changes to branch 'iss2' and do it.
```git
git checkout iss2
```

4. Merge iss2 to master
Firstly, we should re-base iss2 (get new code from master to iss2).
```git
git rebase
```
And then make a pull request.