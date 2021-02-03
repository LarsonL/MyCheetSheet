# Basic commands and operation

## Navigation through a file by cursor
Ops/Cmd | Descriptions
|:--:|:--:|
`h` | Move the cursor *left*
`j` | Move the cursor *down*
`k` | Move the cursor *up*
`l` | Move the cursor *right*
`w` | Move the cursor to the head of next word
`b` | Move the cursor to the head of previous word
`e` | Move the cursor to the end of next word
`{` | Move the cursor to previous block
`}` | Move the cursor to next block

## Navigation through a file by page
Ops/Cmd | Descriptions
|:--:|:--:|
`<C-u>` | Move up a page
`<C-d>` | Move down a page
`<C-e>` | Move up a line
`<C-y>` | Move down a line

## Normal Mode Operations
Ops/Cmd | Descriptions
|:--:|:--:|
`dd` | Cut a line
`#yy` | Yank # lines (# is optional)
`p` | Paste

## Switching to Insert Mode
Ops/Cmd | Descriptions
|:--:|:--:|
`i` | Switch to "Insert Mode" and the cursor is at current character
`I` | Switch to "Insert Mode" and the cursor is at the start of the line
`a` | Switch to "Insert Mode" and the cursor is after the character
`A` | Switch to "Insert Mode" and the cursor is at the end of the line
`o` | Switch to "Insert Mode" and the cursor starts at a blank line in next line
`O` | Switch to "Insert Mode" and the cursor starts at a blank line in previous line

## Switching to Visual Mode
Ops/Cmd | Descriptions
|:--:|:--:|
`v` | Enter visual block
`<C-v>` | Enter visual block mode (Unix)
`<C-q>` | Enter visual block mode (Winodows)

## File operations
Ops/Cmd | Descriptions
|:--:|:--:|
`:w<CR>` | Write the buffer to the file
`:q<CR>` | Quit the vim program

