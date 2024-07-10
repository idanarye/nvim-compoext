[![CI Status](https://github.com/idanarye/nvim-compoext/workflows/CI/badge.svg)](https://github.com/idanarye/nvim-compoext/actions)

INTRODUCTION
============

SETUP
=====

Install Compoext with your plugin manager of choice, and add this to your `init.lua`:

```lua
require'compoext'.setup {
}
```

CONTRIBUTION GUIDELINES
=======================

* If your contribution can be reasonably tested with automation tests, add tests.
* Documentation comments must be compatible with both [Sumneko Language Server](https://github.com/sumneko/lua-language-server/wiki/Annotations) and [lemmy-help](https://github.com/numToStr/lemmy-help/blob/master/emmylua.md). If you do something that changes the documentation, please run `make docs` to update the vimdoc.
* Compoext uses Google's [Release Please](https://github.com/googleapis/release-please), so write your commits according to the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format.
