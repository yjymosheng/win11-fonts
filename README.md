# windows font for archlinux

| 字体名称  | Windows 文件名|
|----------|------------|
| 楷体	   | simkai.ttf |
| 黑体	   | simhei.ttf |
| 宋体	   | simsun.ttc |
| 仿宋	   | fangsong.ttc |

## 📥 安装方法

将本仓库中的字体文件复制到本地用户字体目录中

```bash
mkdir -p ~/.local/share/fonts
cp ./fonts/* ~/.local/share/fonts/
fc-cache -fv
```

或者

```bash
sudo cp ./fonts/* /usr/share/fonts/
sudo fc-cache -fv
```
