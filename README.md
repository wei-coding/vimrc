# vimrc

```
set encoding=utf8
set fileencodings=utf8

set nu
set ai
set cursorline
set tabstop=4
set shiftwidth=4
set hlsearch
set cindent
set laststatus=2
set wrap

inoremap ( ()<Esc>i
inoremap {<CR> {<CR>}<Esc>ko
inoremap {{ {}<ESC>i
inoremap [ []<Esc>i
inoremap #in #include<><Esc>i
inoremap " ""<Esc>i
inoremap ' ''<Esc>i


filetype indent on

syntax enable
```