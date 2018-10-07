# Vim Pro
## Benefit
- Cool
- Exist on all Unix system
- Productivity

## Disadvantage
- Addictive

## Tools
- neovim
- vim

## install neovim
brew install nvim or pip install nvim

## Commands
:q - exit
:w <file_name>- save
:wq - save & exit
:q! - force exit
:wq! - force save & exit
:set nu - show line number
:noh - no highlight
. - repeat last command
:set clipboard=unnamed - sync clipboard inside and outside editor

## Mode
- normal mode
- visual mode
- insert mode

## How to move in vim
- j - Up (move to next 5 line use 5j)
- k - Down
- h - Left
- l - Right
- gg - Move to Top
- G - Move to Bottom
- % - Move to backlet {  } [ ] ( )  
- ctrl+f(orward) - end line at bottom screen
- ctrl+b(ackward) - begin line at top screen
- ctrl+d(own) - down next screen
- ctrl+u(p) - up previous screen

## How to change into insert mode
- i - insert
- I - prepend
- a - append
- o - insert next line
- O - insert previous line
- r - replace 
- R - replace all  

## How to remove 
- x - remove a charactors (remove n character use <n>x)
- D - remove from cursor to end of line
- C - remove from cursor to end of line and change to insert mode
- dd - remove line (remove n line use <n>dd)
- dw - remove word from cursor (remove n word use <n>dw)  
- diw - remove word (wherever cursor is on word) 
- daW - remove word with comma and space, to next word

## Back to normal mode 
- esc - back to normal mode
- u - undo
- ctrl + r - redo
- g + ; - last action select
- g + i - last action select + change into insert mode
- w - go -> I - insert -> Esc every line will get into first next word
- e - go to last next word
- b - go to first previous word
- 0 - go to begin of egin the line
- $ - go to end of the line
- ^ - go to begin of the line that not white space
- yy - copy line
- yw - copy word from cursor
- yiw - copy word 

## how to change into visual mode
- v - visual (drag)
- V - visual line (drag one line)
- ctrl + v - visual block (drag a rectangle) 
- v + i + (', ",{,[,() -> remove all in ',",{,[,(
- v + a + (', ",{,[,() -> remove all in ',",{,[,( include ""
- c - replace and change to insert mode
- d - remove 
- y - copy 
- p - paste
- U - upper case
- u - lower case 
- < - remove indent
- > - add indent 
- gg=G - format indent in file
- == format indent

## Use case of visual block
- ctrl + v -> U - change all to Upper case
- ctrl + v -> I - insert -> Esc every line will get it

## Search word 
- f + <char> - find first charactor in line
- t + <char> - find first charactor but stop before that charactor
- * - search current word
- / search word
- n - Next word
- N - Previous word

## Use case of replace using regex
:10,12 s/vim/VIM/g 
:s/vim/VIM/gc - c will ask for replace
- ctrl + v -> :s/vim/VIM/g - replace only drag

## split screen
:vs,:vsplit - split vertical
:split - split horizontal
ctrl+w + ctrl+w - switch screen
ctrl+w+h - switch to left
ctrl+w+j - switch to up
ctrl+w+k - switch to down
ctrl+w+l - switch to right
