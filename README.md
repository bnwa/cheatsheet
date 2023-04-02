## (Neo)Vim

### Rename a buffer without write
`f[ile]  {name}`

### Write a buffer with a new file name
`:sav[eas] {name}

### Open or write a file and ensure all ancestor directories are created
`e[dit] ++p`
`w[rite] ++p`

### Open related file under cursor in a new window
`<C-w><C-f>`

### Assign a local arguments list to a window
`:argl[ocal] {arglist}`

#### Then revert back to global argument list
`:arg[global]`

#### Or assign a copy of the global argument list to a window
`:argl[ocal]`

