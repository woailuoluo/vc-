# vim-perl6
Improved support for Perl 6 in Vim.

## Installation
Installation of this plugin can be done via any of the available plugin
managers, such as [Pathogen][pathogen], [vim-plug][vim-plug], [vundle][vundle]
or any other one.

Once installed, all files ending in `.pl6`. `.pm6` or `.p6` will make use of
the plugin's features.

## Configuring optional features
Not all features are enabled by default. This is in part due to them still
being considered in testing, or because they may influence your regular
workflow too much. These can be enabled by setting a certain variable to a
truthy value.

### Unicode ops
`vim-perl6` can use Vim's abbreviation feature to convert ASCII based operators
to their Unicode equivalents on the fly. To enable this feature, add the
following line to your `vimrc` file:

```
let g:perl6_unicode_abbrevs = 1
```

[pathogen]: https://github.com/tpope/vim-pathogen
[vim-plug]: https://github.com/junegunn/vim-plug
[vundle]: https://github.com/gmarik/Vundle.vim
