# ctags definition for Rust

## To use

1. Check this repository out somewhere and put that directory on your path.
2. Run `rust-ctags src` (or `rust-ctags src1 src2` etc).
3. This will create a `TAGS` file.

## Emacs vs vim

By default, rust-ctags produces an emacs-style TAGS file. If you want
to use vim style tags, Try `rust-ctags --vim src`.
