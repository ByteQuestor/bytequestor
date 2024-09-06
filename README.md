# README

记录一下第一次上传`Github`

面板创建了仓库以后，复制仓库地址 -> https://github.com/ByteQuestor/bytequestor.git

命令看第二次提交

1，初始化仓库

````git
git init
````

![image-20240906171654478](E:\root\this\Desktop\ByteQuestor\README.assets\image-20240906171654478.png)

2，配置远程仓库

```git
git remote add origin https://github.com/ByteQuestor/bytequestor.git
```



3，上传中转仓库

```git
git add .
```

![image-20240906171817769](E:\root\this\Desktop\ByteQuestor\README.assets\image-20240906171817769.png)

3，提交

```git
git commit -m '这里是提交记录'
```

4，配置代理服务器（看情况，如果push不上去就配一下）

```git
git config --global http.proxy http://127.0.0.1:52479
```

5，查看本机分支名字

（因为以前用的是master，现在是main，所以出现本地和github不一样的情况也无法push）

```git
git branch
```

![image-20240906172511545](E:\root\this\Desktop\ByteQuestor\README.assets\image-20240906172511545.png)

修改主机名字（如果是main就不用修改）

```git
git branch -m master main
git push -u origin main
```

6，将文件推送至远程仓库（含需要配置代理的情况

```git
git push -u origin main
```

![image-20240906173028560](E:\root\this\Desktop\ByteQuestor\README.assets\image-20240906173028560.png)

