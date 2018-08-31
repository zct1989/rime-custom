# rime-custom

### 鼠须管输入法-个人配置

鼠须管常用配置，便于重新部署使用，主要扩展功能：

1. 添加小鹤双拼支持
2. 修改候选字数量为7个
3. 修改候选栏字体样式
4. 修改候选栏布局方向
5. 添加扩展词库

### 使用方法

1.切换至Rmie目录下

```
# mac
# ~/Library/Rime
```

2.检出扩展配置文件

```
# 下载配置文件
git clone https://github.com/zct1989/rime-custom.git .
```

3.重新部署即可


---

过滤生僻字的方法没有测试成功，故使用使用安装花园明朝的方法来解决生僻字显示问题:

```
brew tap jinntrance/homebrew-fonts
#花园明朝字体
brew cask install font-hanamina
```

