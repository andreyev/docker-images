Usage:
```
docker run -ti -v /$HOME/:/$HOME/ -v $HOME/.chef/:/root/.chef/ andreyevbr/chefdk-vim:1.6.11 knife vault edit -e /usr/bin/vim VAULT ITEM
```
