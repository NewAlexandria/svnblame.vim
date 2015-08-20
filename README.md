# SVN Blamo !

##### v1.1

Adds a left-gutter to the current split, showing the SVN blame history for that file.  The blame split is scroll-bound to the main window, so you can read in sync.

Bind it to a key in your `.vimrc`

    map <leader>s :call SvnBlame()<CR>


## Dependencies

* `svn` 1.6
* `awk`

----

Thanks to Jonty for the base, and Jim Mahood for the tips

## License

[MIT](http://mit-license.org/)
