Fancy symbols
-------------

Airline allows you to use fancy symbols on the status line for breadcrumbs and indicators (example: a padlock when editing read-only files). And vim-devicons also has fancy symbols for the files in NERDTree (the file explorer), like a python logo for python files, etc. Using them requires having a patched font in your terminal. It may sound like black magic, but it's just downloading, installing and using a font from this website:

`Nerd Fonts <https://github.com/ryanoasis/nerd-fonts#patched-fonts>`_

I recommend just manually downloading the one you like the most from `this list <https://github.com/ryanoasis/nerd-fonts#patched-fonts>`_.

**Configure**

After installing the font, go to the settings of your terminal app and select the patched font. Finally, open your ``init.vim`` and uncomment:

- the line declaring the vim-devicons plugin (search for "Nice icons")
- the lines at the end of the file, after the comment that explains that those are the lines for the fancy symbols.

That's it! Restart your vim and enjoy the beauty of a modern terminal :D
