terraform-snippets.vim
===

This is vim snippets for [Terraform](//terraform.io/) inspired by [serverspec-snippets](//github.com/glidenote/serverspec-snippets).

Install
---

### Neobundle

1. Setup the [neobundle](https://github.com/Shougo/neobundle.vim) package manager
2. Set the bundles for [itamae-snippets](https://github.com/tacahilo/itamae-snippets)

``` vim
NeoBundle 'tacahilo/itamae-snippets'
```

3. Open up Vim and start installation with `:NeoBundleInstall`

### Vundle

1. Setup the [vundle](https://github.com/gmarik/vundle) package manager
2. Set the bundles for [itamae-snippets](https://github.com/tacahilo/itamae-snippets)

``` vim
Bundle 'tacahilo/itamae-snippets'
```

3. Open up Vim and start installation with `:BundleInstall`

## Setup

Set itamae-snippets directory(`~/.vim/bundle/terraform-snippets.vim`) in your .vimrc.


``` vim 
" setting example
let g:neosnippet#snippets_directory = [
      \'~/.vim/snippets',
      \'~/.vim/bundle/terraform-snippets.vim',
      \]
```

### Usage

open *.tf files and set filetype `terraform`

``` vim
:set ft=terraform
```

or terraform plugins:

- https://github.com/markcornick/vim-terraform
- https://github.com/bkad/vim-terraform

## License

Lcense: Same terms as Vim itself (see [license](http://vimdoc.sourceforge.net/htmldoc/uganda.html#license))
