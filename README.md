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


# 批量创建文件
```
mkdir -p  /opt/k8s/{bin,abc,add}

```
