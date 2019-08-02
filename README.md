# phpstorm-config
phpstorm配置备份


.ideavimrc

```bash
set surround
set encoding=utf-8
set nu
set relativenumber
set incsearch
set ignorecase
" set ic
set hlsearch
set nowrapscan
set showmatch
nnoremap 0 ^
nnoremap ,z :wq<CR>
nnoremap <esc> :nohl<cr>
nnoremap <esc> :nohls<cr>
inoremap zz <esc>zz
inoremap jk <esc>
nnoremap Y yg_
inoremap <C-j> <Down>
inoremap <C-k> <Up>

" 将当前行上下移
noremap <C-j> :m .+1<CR>
noremap <C-k> :m .-2<CR>

nnoremap <space>u :action FindUsages<cr>
nnoremap zh :action PreviousTab<CR>
nnoremap zl :action NextTab<CR>
nnoremap ,q :action CloseAllEditors<CR>
nnoremap <tab> :action NextSplitter<CR>
nmap ,m :action FileStructurePopup<CR>

" 在project中显示当前文件
nnoremap <space>e <ESC>:action SelectInProjectView<CR>
nnoremap <C-O> :action Back<CR>
nnoremap <C-I> :action Forward<CR>

nnoremap <space>s <ESC>:source ~/.ideavimrc<CR>
nnoremap <space>i <ESC>:e ~/.ideavimrc<CR>

nnoremap <space>l <ESC>:action KJumpAction.Line<cr>

" 命令模式下 Ni$ <esc> 连续插入N个$, 比如 9ia<esc> 连续插入9个a，这在写分割线的时候很方便
```
