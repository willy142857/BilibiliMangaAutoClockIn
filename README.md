# Bilibili 漫畫自動簽到

## Docker

```
docker run -it \
--restart=always \
--name=manga \
willy142857/bilibilimangaautoclockin \
$username $password
```

Or

```
docker run -it \
--restart=always \
--name=manga \
willy142857/bilibilimangaautoclockin \
$username $password \
$accesstoken $refreshtoken
```
