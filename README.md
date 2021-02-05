# node ace zsh completion

To install it, you need to download the file `_node_ace` and put it in folder covered by your `fpath`.

Since I failed to apply the script to the `node ace` command, this script applies to the command `na`.

Unfortunately, aliases like `alias na="node ace"` breaks the completion, so I added a little function in my `.zshrc` :

```sh
na() {
    node ace "$@"
}
```
