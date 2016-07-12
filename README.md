# Template

## `wget`

Create a new inuitcss-compatible file by running the following command inside of
your CSS directory:

```
$ wget git.io/inuitcssnew -O _<layer>.<file>.scss
```

For example:

```
$ wget git.io/inuitcssnew -O _components.buttons.scss
```

## `curl`

If you do not have `wget` installed, you can try `curl`:

```
$ curl -L git.io/inuitcssnew -o _<layer>.<file>.scss
```

For example:

```
$ curl -L git.io/inuitcssnew -o _components.buttons.scss
```

## Save Page As…

If you do not want to use the command line, [head
here](https://raw.githubusercontent.com/inuitcss/template/master/_layer.file.scss)
and save the file into your project in the correct `_<layer>.<name>.scss`
format.
