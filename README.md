# hexo blog

## 安装

```
	npm install hexo-cli -g  # 先安装hexo的脚手架
	git clone git@github.com:qqsupper/qqsupper.github.io.git  # 下载项目，因为hexo 是默认分支，所以这里直接会下载hexo分支
	npm i # 安装依赖
	hexo s # 启动服务器

```

### 同步第三方主题

在博客根目录执行如下操作。

```
  git submodule init	# 初始化本地配置文件
  git submodule update    # 拉取子模块
```

如果第三方主题有修改的，修改完成后在第三方主题目录执行。

```
  git add . 			# 所有变化提交到暂存区
  git commit -m "修改主题xxxx"  	# 提交文件
  git push origin master   	# 推送master分支
```