$ git init
$ git add index.html
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin https://github.com/ynby2018/ynby2018.github.io.git
$ git config --global --unset http.proxy
$ git config --global --unset https.proxy
$ git config --global http.sslVerify false
$ git push -u origin main

$git pull 将远程库的文件同步到本地