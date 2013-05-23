## Clone from [raphael-proust/ocaml_lwt.vim](https://github.com/raphael-proust/ocaml_lwt.vim)
* * *
> Clone the bondi.vim file into ~/.vim/syntax/. Then stick these of lines into your .vimrc (this file has to be placed in home directory)

    au BufRead,BufNewFile *.bon set filetype=bondi
    au! Syntax bondi source ~/.vim/syntax/bondi.vim
    autocmd Syntax bondi set commentstring=(*%s*)
