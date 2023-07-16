- ssh key 등록
```
ssh-copy-id -i <ssh public key> <username>@<server ip>
예) ssh-copy-id -i .ssh/id_rsa.pub wastest@10.100.1.10
```

- config
```
vi ~/.ssh/config

# add
Host twig-remote
User twig
HostName 219.248.110.167
Port 1234
IdentityFile ~/.ssh/id_rsa
RequestTTY force
RemoteCommand cd /home/twig/wymin && zsh
```

