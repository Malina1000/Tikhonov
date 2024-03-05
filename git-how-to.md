# how to create ssh key

1. Run ssh-keygen -t ed25519 -C "my GItHub email"
2. Press enter twice
3. github account > settings > ssh and gpg keys > new ssh key and then paste what is inside .pub file in ssh folder, add ssh key
4. git -T git@github.com - to check if everything is ok 
5. git remote add origin %link from github repo page%

git remote -v - to check if everything is ok
