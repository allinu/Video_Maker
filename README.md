# Video Maker

> 视频生成器

## 项目描述

使用
Python，以及`moviepy`根据图片创作出视频，使用`rich`优化控制台输出样式，代码执行不会破坏素材源文件

## 目录介绍

目录主要分为`必要目录`和`自动生成目录`，必要目录随项目下载就存在，不能删除，并且里面需要放置生成视频所需要的图片素材文件，图片素材文件格式可以为`jpg`,`png`,`jpeg`，暂不支持其他格式


### 必要目录

- `src/images`: 存放原始图片
- `src/music`: 存放 BGM

### 自动生成目录

- `tmp/`: 程序执行过程中中间文件的存储路径（运行完毕自动清理）
- `dist/`: 输出视频存放目录


### 使用方法

1. 下载 / 克隆仓库文件到本地

```shell
git clone https://github.com/allinu/Video_Maker.git
```

2. 将图片及 BGM 拷贝至指定目录

3. 创建本地虚拟环境

```shell
virtualvenv venv
```
4. 安装 Python 的必要模块

```shell
source ./venv/bin/activate
pip install -r requirements.txt
```
5. 执行`run.py`文件

```shell
python run.py

```


## TODOs

- [ ] 自动生成视频
- [ ] 支持 BGM 添加
- [ ] 支持片头添加介绍文字
- [ ] 支持自动发布视频到 Bilibili
- [ ] 支持配置文件
