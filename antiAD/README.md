# Sing-box anti converter from adgurad

```sh
./sing-box rule-set convert --type adguard --output anti_spotify.srs ./ant-spotify.txt
```

# Adguard snippet

||example.com^ 拦截 example.com 及其子域名的所有请求。

@@||example.com^ 将允许 example.com 的所有请求，不会被拦截。

# Spotify white list

```txt
@@||login5.spotify.com^
@@||spclient.wg.spotify.com^
@@||open.spotify.com^
@@||api-partner.spotify.com^
@@||partners.wg.spotify.com^
@@||api.spotify.com^
@@||audio4-fa.scdn.co^
@@||seektables.scdn.co^
```
