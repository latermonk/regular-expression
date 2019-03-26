# regular-expression




# 查找文件并列出来
```

find / -exec ls -l {} \;

find /root  -exec ls -l {} \;

```


# 查找文件并删除

```

ls |grep -v pem | xargs -i rm {}

```
