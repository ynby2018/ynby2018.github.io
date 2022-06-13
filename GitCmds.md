```
$ git add index.html
$ git commit -m "first commit"
$ git branch -M main

$ git push -u origin main
```
# 第一次将远程代码同步到本地
```
$ git config --global user.name "xxx"
$ git config --global user.name "xxx"
$ git remote add origin https://github.com/xxx/xxx.github.io.git
$ git init
$ git config --global --unset http.proxy
$ git config --global --unset https.proxy
$ git config --global http.sslVerify false
$ git pull origin main # 将远程库的文件同步到本地

```
# 加速git访问
> https://github.com/dotnetcore/fastgithub/releases
