# vim-workman
Simple vim key bindings for the workman layout. Just paste the code in your .vmrc

Original idea taken from Tim DuBois's [blog post](https://axiomatic.neophilus.net/posts/2013-08-13-workman-layout-for-vim.html).

### Features
- Keybidings for the most frequent keys.
- Quick change between layouts. Use ```<Leader>w``` to change to workman and
```<Leader>q``` to change to Qwerty.
- Change startup default. Use the desired layout in the following line:
```
autocmd VimEnter * call Keyboard("workman")
```
- Use ```nn``` in Workman and ```jj``` in Qwerty to exit Insert mode.
- Comments for each key e.g.
```
" --- Movement ---
  noremap o l|          " move right
  noremap e k|          " move up
  noremap n j|          " move downn
  noremap y h|          " move left

  noremap <C-f> <C-u>|  " move half page up
  noremap <C-h> <C-d>|  " move half page down
  noremap <C-v> <C-b>|  " move one page up
  noremap <C-t> <C-f>|  " move one page down
  noremap <C-r> <C-e>|  " scroll text up
  noremap <C-j> <C-y>|  " scroll text down

  noremap Y H|          " move to top of screen
  noremap L M|          " move to middle of screen
  noremap O L|          " move to bottom of screen
```
