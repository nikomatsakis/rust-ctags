ctags definition for Rust

To use:

1. Check this repository out somewhere and put that directory on your path.
2. Run `rust-ctags src` (or `rust-ctags src1 src2` etc).
3. This will create a `TAGS` file.

By default, rust-ctags produces an emacs-style TAGS file. If you want
to use vim style tags, edit the script and remove the `-e`
argument. Or, better yet, just use emacs instead.
