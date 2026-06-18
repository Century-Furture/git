# git

```cmd
:: 清除全局代理
git config --global --unset http.proxy
git config --global --unset https.proxy
git config --global --unset http.https://github.com.proxy

# 只设置GitHub走代理，端口根据vpn来
git config --global http.https://github.com.proxy http://127.0.0.1:7890

# http/https 根据vpn的端口设置，vpn端口为7892，就设为7892
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy http://127.0.0.1:7890
```

