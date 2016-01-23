# Some advanced Vim shortcuts

`f`/`F` + key: Jump to character on the current line  
`df` + key: Delete everythting up to and including that character on this line   
`diw`: Delete current word, similar to `bwd`  
`di"`: Delete everything in quotes  
`di(`: Delete everything in these parenthesis, `(` is replaceable  
`10j`/`10k`: Jump 10 lines down or up, useful with relative line numbers  
`Ctrl+H`/`Ctrl+M`/`Ctrl+L`: Jump to the top, middle or bottom of the current buffer view  
`gd`: Go to definition  
`.`: Repeat last command  
`:%s/foo/bar/g`: Find each occurrence of 'foo' (in all lines), and replace it with 'bar'.  
`:s/foo/bar/g`: Find each occurrence of 'foo' (in the current line only), and replace it with 'bar'.  
`:%s/foo/bar/gc`: Change each 'foo' to 'bar', but ask for confirmation first.  

[Credit for the last three](http://vim.wikia.com/wiki/Search_and_replace)

More good motion shortcuts [here](http://vimdoc.sourceforge.net/htmldoc/motion.html). (Disclaimer: It's Sourceforge)