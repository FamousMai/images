# Github图床  + Typora，实现图片自动上传

### 1、下载工具 PicGo

https://github.com/Molunerfinn/PicGo

### 2、设置Github，新增token

- 从这里进入 [Settings / Developer settings](https://github.com/settings/tokens) 设置 Generate new token
- 保存token，后面第4步要用到
### 3、创建用于存放图片的仓库

如：images

### 4、配置 PicGo，图床设置/GitHub

- 设定仓库名：`FamousMai/images`（第3步创建的仓库）
  - 格式：:user/:repo

- 设定分支名：`master`（自定义）
- 设定Token：`***************`（第2步获取的token）
- 设定存储路径：`imgs/`（自定义）
- 设定自定义域名：`https://cdn.statically.io/gh/famousmai/images/master/images.jpg`
  - 格式：https://cdn.statically.io/gh/:user/:repo/:tag/:file
  - 官网：[https://statically.io](https://statically.io)（这里用了，免费的GitHub的cdn域名）

### 5、Typora设置 图片/上传服务设定
选择 PicGo 进行上传

