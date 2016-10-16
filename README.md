## Jekyll

### workflow
```
gem install jeykll
jekyll s
```

### deploy
```
jekyll build
s3cmd sync _site/. s3://shaunrussell.com
```
