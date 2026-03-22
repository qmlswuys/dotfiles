# Dotfiles
![](./screenshot/26_03_23.png)

## 🖥️ 环境概览

| 组件 | 软件 |
|------|------|
| 窗口管理器 | niri |
| 终端模拟器 | foot |
| 状态栏 | waybar |
| 字体 | JetBrainsMono Nerd Font, Noto Sans CJK，monaspace |
| 壁纸 | swaybg wbg |
| 文件管理器 | yazi |
| Shell | fish |
| 剪贴板 | wl-clipboard |
| 剪贴板管理 | cliphist |
| 身份验证代理 | polkit-gnome |


## 🚀 安装步骤

```bash
# 1. 克隆仓库
mkdir ~/code
git clone https://github.com/your-username/dotfiles.git ~/code/dotfiles

# 2. 创建符号链接
ln -s ~/code/dotfiles/fontconfig/fonts.conf ~/.config/fontconfig/fonts.conf
ln -s ~/code/dotfiles/niri ~/.config/niri
ln -s ~/code/dotfiles/waybar ~/.config/waybar
ln -s ~/code/dotfiles/foot ~/.config/foot
ln -s ~/code/dotfiles/yazi ~/.config/yazi

# 3. 刷新字体缓存
fc-cache -fv
```

