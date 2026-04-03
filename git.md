ssh-keygen -t ed25519 -C "ydnx-klochkov-alex@yandex.ru" -f github
ssh -T git@github.com -i github

Commands:
- git status
- git add --all
- git commit -m 'Commit message'
- git log