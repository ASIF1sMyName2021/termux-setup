set viminfo="NONE"

set nowrap
set number
set incsearch
set hlsearch
set background=dark
filetype on
filetype plugin on
filetype indent on

syntax on
set t_Co=256
colorscheme gruvbox

set noshowmode

" Statusline
set laststatus=2
set statusline=                          " left align

set statusline+=%#NormalColor#%{(mode()=='n')?'\ \ NORMAL\ ':''}
set statusline+=%#InsertColor#%{(mode()=='i')?'\ \ INSERT\ ':''}
set statusline+=%#ReplaceColor#%{(mode()=='R')?'\ \ REPLACE\ ':''}
set statusline+=%#VisualColor#%{(mode()=='v')?'\ \ VISUAL\ ':''}

set statusline+=%1*\ %f                  " short filename
set statusline+=%=                       " right align
set statusline+=%*
set statusline+=%3*\%h%m%r               " file flags (help, read-only, modified)
set statusline+=%3*\%l/%L\\|             " line count
set statusline+=%3*\%y                   " file type

hi User1 ctermbg=black ctermfg=grey guibg=black guifg=grey
hi User2 ctermbg=150 ctermfg=black guibg=green guifg=black
hi User3 ctermbg=black ctermfg=150 guibg=black guifg=lightgreen

hi NormalColor guifg=Black guibg=Green ctermbg=150 ctermfg=0
hi InsertColor guifg=Black guibg=Cyan ctermbg=180 ctermfg=0
hi ReplaceColor guifg=Black guibg=maroon1 ctermbg=165 ctermfg=0
hi VisualColor guifg=Black guibg=Orange ctermbg=202 ctermfg=0

