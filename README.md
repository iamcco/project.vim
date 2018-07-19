# project.vim

- auto change the cwd to the project directory
- denite source for jump bewteen projects

## install

> only support neovim

```bash
npm install -g neovim
```

```vim
Plug 'iamcco/project.vim'
```

## config

- `g:path_to_save_project` data to save
- `Denite project` to open project list

## Denite action

- `open` open project directory
- `delete` delete project from the list
