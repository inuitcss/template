# Template

inuitcss has very specific formatting and whitespace rules. To make it easier
for developers to follow these rules, there is a simple template file available.
To ensure your Sass is inuitcss- and ITCSS-compatible, it is recommended that
you use this template as the basis for all of your additions to an inuitcss
project.

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
