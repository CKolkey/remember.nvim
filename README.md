# remember.nvim

| version                                                                |
| :--------------------------------------------------------------------: |
| [v1.3.1](https://github.com/vladdoster/remember.nvim/releases)         |

A port of the Vim plugin
[vim-lastplace](https://github.com/farmergreg/vim-lastplace). It uses the same
logic as `vim-lastplace`, but leverages the Neovim Lua API.

Intelligently reopen files at your last edit position. By default git, svn, and
mercurial commit messages are ignored because you probably want to type a new
message and not re-edit the previous one.

## Features

Uses new Neovim `0.7` Lua `vim.nvim.create_autocmd` function.

## Usage

### Packer

```Lua 
-- Using Packer
use({ 'vladdoster/remember.nvim', config = [[ require('remember') ]] })
```

For the full documentation, see [remember.txt](doc/remember.txt).

## Issues

If you believe you've found a bug or shortcoming in remember.nvim that is
neither addressed by help nor in existing issues, please open an issue with
clear reproduction steps. 

## Contributing

All PRs are welcome. If you are planning to contribute a large patch, please
create an issue first to get any upfront questions or design decisions out of
the way first.

## License

The MIT License - see [LICENSE](LICENSE) for more details.
