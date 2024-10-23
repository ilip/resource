# Sing-box anti converter from adgurad

```sh
./sing-box rule-set convert --type adguard --output anti_spotify.srs ./ant-spotify.txt
```

# Adguard snippet

||example.com^ 拦截 example.com 及其子域名的所有请求。

@@||example.com^ 将允许 example.com 的所有请求，不会被拦截。
