## 检测网站是否在线

先Fork该仓库，然后直接在Github上修改`.github/workflows/ping.yml`文件中的域名即可

```
...
run: Web.Ping --host http://www.zkea.net
```

**注意：** Fork后Actions默认是关闭的，需要手动开启。

### Ping

https://github.com/SeriaWei/Ping

http://www.zkea.net/codesnippet/detail/ping-website.html
