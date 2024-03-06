### MEGA GUIDE GIT_HOW_TO

## Creating the key:
- ls ~/.ssh
- ssh-keygen -t ed25519 -C "email.@email"
- eval "$(ssh-agent -s)"
- ssh-add ~/.ssh/id-ed25519
- cat ~/.ssh/id_ed25519.pub
- Now copy the shown key into your github account
- Check if you've done all allright with 'ssh -T git@github.com"
