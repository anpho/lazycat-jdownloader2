# JDownloader2 for LazyCat Microserver.

### Base Image

[jlesage/jdownloader-2](3), cached to LazyCat's registry for best performance.

### Download 

LazyCat's AppStore,  waiting for approval.

### How to build from 0

1. Retrive official docker image 
```
lzc-cli appstore copy-image jlesage/jdownloader-2:latest
```
2. edit `lzc-manifest.yml`
3. Build and publish lpk. 
```
lzc-cli project build
lzc-cli appstore publish ./your-app.lpk
```

### Contact

[Twitter](https://x.com/anpho)


[1]:https://www.resilio.com/
[2]:https://lazycat.cloud/
[3]:https://hub.docker.com/r/jlesage/jdownloader-2
[4]:https://lazycat.cloud/appstore/#/shop/detail/anpho.lzcapp.resilio