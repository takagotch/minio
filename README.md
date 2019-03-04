### minio
---
https://github.com/minio/minio

```
docker pull minio/minio
docker run -p 9000:9000 minio/minio server /data

docker pull minio/minio:edge
docker run -p 9000:9000 minio/minio:edge server /data


brew install minio/stable/minio
minio server /data

brew install minio
brew install minio/stable/minio

chmod 755 minio
./minio server /data

weget https://dl.minio.io/server/minio/release/linux-pcc641e/minio
chmod +x minio
./minio server /data

minio.exe server D:\Photos

pkg install minio
srsrc minio enable=yes
sysrc minio_disks=/home/user/Photos
service minio start

go get -u github.com/minio/minio

iptables -A INPUT -p tcp --dport 9000 -j ACCEPT
service iptables restart

iptables -A INPUT -p tcp --dport 9000:9010 -j ACCEPT
service iptables restart

ufw alllow 9000
ufw allow 9000:9010/tcp

firewall-cmd --get-active-zones
fireware-cmd --zone=public -add-port=9000/tcp --permanent
firewall-cmd --reload
```

```
```

```
```


