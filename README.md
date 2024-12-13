# 

```
curl https://redturtle.github.io/ppa/KEY.gpg | sudo gpg --dearmor --yes --output /etc/apt/trusted.gpg.d/redturtle-repo.gpg

echo "deb https://redturtle.github.io/ppa ./" > /etc/apt/sources.list.d/redturtle.list

apt update

apt upgrade
```

## TODO

* [ ] distributions

