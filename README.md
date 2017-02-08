# Selenium grid

## Install

```bash
git clone https://github.com/amokrushin/iamselenium

cp example.vpn.env vpn.env
# edit vpn.env

docker-compose up -d

docker-compose scale chrome=2 firefox=5
docker-compose scale chrome=1 firefox=0

docker-compose down
```


## TODO: Windows VPN client setup
