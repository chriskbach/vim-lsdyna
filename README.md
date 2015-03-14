#vim-lsdyna
[VIM](http://www.vim.org/) filetype plugin for [Ls-Dyna](http://www.lstc.com) FE solver.

What is Ls-Dyna filetype plugin?

It's just bunch of VIM scripts to speed up work with Ls-Dyna keyword file.

##Main features
- Syntax highlighting
- Folding
- Keyword library
- Useful commands, functions and mappings

###Syntax highlighting
With color syntax it's easier to navigate through a keyword file.

![vimLsDynaColorSyntax](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/syntax.gif)

###Folding
Node & element table folding, no more never ending scrolling!

![vimLsDynaFold](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/folding.gif)

See VIM documentation for details about foldings: `:help usr_28`

###Keyword library
With keyword library you can very quick add a new Ls-Dyna keyword into your model.

![vimLsDynaKeyLib](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/library.gif)

Check `:help lsdyna-keywordLibrary` to see how to work with the library.

###Curve commands
You can use commands to operate with curve data directly in VIM.

![vimLsDynaScale](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/commands.gif)

See `:help lsdyna-commands` for list of all commands and examples of use.

###Commands, functions & mappings
The plugin has couple of great functions to make your work even faster:
- mappings
- comment/uncomment
- data line autoformating
- keyword text objects
- include path

Read chapter 6 of the plugin documentation `:help lsdyna-mappings` to know all of them.

##Installation

[Pathogen](https://github.com/tpope/vim-pathogen)

```
cd ~/.vim/bundle
git clone https://github.com/gradzikb/vim-lsdyna
```

##Documentation

The plugin has decent [documentation](https://github.com/gradzikb/vim-lsdyna/blob/master/doc/lsdyna.txt) with detail explanation of all functions and examples.

Please read the documentation before you start using the plugin.

`:help lsdyna`

##License

The GNU General Public License

Copyright &copy; 2014 Bartosz Gradzik
