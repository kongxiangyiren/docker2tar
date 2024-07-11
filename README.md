# 拉取镜像

1、修改 matrix 的 image

![alt text](img/image.png)

2、在 actions 运行成功后会上传 image.zip 文件

![alt text](img/image-1.png)

# 导入镜像

1、解压 image.zip 文件 得到 image.tar 文件
![alt text](img/image-2.png)

2、上传 image.tar 文件到服务器

3、运行导入命令

```sh
docker load -i image.tar
```

![alt text](img/image-3.png)
