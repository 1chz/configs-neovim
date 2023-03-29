# [Neovim](https://neovim.io/)

## Neovim 설치

```shell
# python 설치 (이미 3.7이상이 설치돼있으면 생략)
# brew install python

# neovim 설치
$ brew install neovim

# ctags 설치 (이미 설치돼있으면 생략)
$ brew install ctags

# nvm 설치 (이미 설치돼있으면 생략)
# 설치후 프롬프트에 출력되는 export를 shell에 설정
$ brew install nvm 

# lastst node 설치 (이미 설치돼있으면 생략)
$ nvm install node

# vim-plug 설치 (이미 설치돼있으면 생략)
$ sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

# 이 저장소의 init.vim을 붙여넣고 저장
$ nvim ~/.config/nvim/init.vim

# 이 저장소의 coc-settings.json를 붙여넣고 저장
$ nvim ~/.config/nvim/coc-settings.json 

# nvim 편집기를 연 상태에서 PlugInstall 명령어를 입력하여 vim 플러그인 설치
$ nvim
$ :PlugInstall

# coc-nvim 설치
$ cd ~/.local/share/nvim/plugged/coc.nvim
$ yarn install
$ yarn build
$ nvim 
$ :CocInstall coc-json coc-python coc-java coc-kotlin coc-clangd coc-snippets

# python 개발환경 설정
$ pip3 install black flake8 jedi 
```

## Key mappings
- ctrl + w - nerdtree
- F8 - ctags
- F9 - black

## Vim 단축키
![image](https://user-images.githubusercontent.com/71188307/228559920-c71d11e1-4a94-406b-9a3d-07d3d1059cee.png)
