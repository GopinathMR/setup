# Instructions to setup github access on EC2 #

- `ssh-keygen -t rsa -C "mr.gopinath@gmail.com" -f id_github`
- Copy below content to ~/.ssh/config

>     Hostremote github
>     
>     Hostnamegithub.com
>     
>     IdentityFile~/.ssh/id_github
    
- paste below key to github ssh keys in settings

	`cat ~/.ssh/id_github.pub`  




- git remote add github git@github:GopinathMR/bitstarter.git



- git remote -v

>     github  git@github:GopinathMR/bitstarter.git (fetch)
>     github  git@github:GopinathMR/bitstarter.git (push)
>     origin  http://github.com/GopinathMR/bitstarter.git (fetch)
>     origin  http://github.com/GopinathMR/bitstarter.git (push)

