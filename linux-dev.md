##### MongoDB not starting in Ubuntu 20.04
Ref: https://askubuntu.com/questions/884541/cant-start-mongodb-service

```
sudo chown -R mongodb:mongodb /var/lib/mongodb 
sudo chown mongodb:mongodb /tmp/mongodb-27017.sock
```
