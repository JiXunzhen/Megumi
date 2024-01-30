# 配置中心

打造完美osx terminal. 梦幻级别的享受.

## macos初始化

1. 安装chrome/raycast/iterm2

2. 安装brew（需要外网）
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

3. 安装vim plugged插件
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

4. 安装zsh插件
brew install zsh-autosuggestions
echo "source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
brew install zsh-syntax-highlighting
echo "source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc



## 环境
* osx
* iterm
* oh my zsh

![我永远喜欢加藤惠](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1516781772368&di=a3c8c206369d709adba9bfa36a4a5318&imgtype=0&src=http%3A%2F%2Fimgup01.hxmeishi.com%2F2017-06%2F21%2F11%2F14980140291650_0.png)
