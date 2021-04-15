

- [git-crypt](https://github.com/AGWA/git-crypt) allows to protect individual files as specified in `.gitattributes`
- [git-remote-gcrypt](https://git.spwhitton.name/git-remote-gcrypt/about/) allows to encrypt entire git remote
    - `git remote add cryptremote gcrypt::git@github.com:nrolland/test-crypt.git`
    - `git push cryptremote master`
