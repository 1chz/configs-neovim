# [Neovim](https://neovim.io/)

## Neovim 설치

```shell
$ brew install neovim
$ brew install ctags
$ brew install nvm # 설치후 프롬프트에 출력되는 export를 shell에 설정
$ nvm install node
$ sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

$ nvim ~/.config/nvim/init.vim # 이 저장소의 init.vim을 붙여넣고 저장
$ nvim ~/.config/nvim/coc-settings.json # 이 저장소의 coc-settings.json를 붙여넣고 저장
$ nvim
$ :PlugInstall

$ cd ~/.local/share/nvim/plugged/coc.nvim
$ yarn install
$ yarn build
$ pip3 install black flake8 jedi 
$ nvim 
$ :CocInstall coc-json coc-python coc-java coc-kotlin coc-clangd coc-snippets
```

## Key mappings
- ctrl + w - nerdtree
- F8 - ctags
- F9 - black

## Vim 단축키
![image](https://user-images.githubusercontent.com/71188307/228559920-c71d11e1-4a94-406b-9a3d-07d3d1059cee.png)
