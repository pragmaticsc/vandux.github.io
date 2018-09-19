## Jekyll

### workflow
```
gem install jeykll
bundle exec jekyll s
```

### deploy
```
bundle exec jekyll build
s3cmd sync _site/. s3://shaunrussell.com
```
