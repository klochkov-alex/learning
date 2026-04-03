ssh-keygen -t ed25519 -C "ydnx-klochkov-alex@yandex.ru" -f github
ssh -T git@github.com -i github

### Commands:
- git status
- git add --all
- git commit -m 'Commit message'
- git log

### How to add remote repo:
```bash
git remote add origin git@github.com:klochkov-alex/learning.git
```
### How to push to remote repo:
```bash
- git push -u origin main #(push main branch to origin; origin is set by --set-upstream a.k.a -u)
```