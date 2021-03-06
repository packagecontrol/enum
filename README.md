# *enum* module for Package Control

This is the *[enum34][]* module
bundled for usage with [Package Control][],
a package manager
for the [Sublime Text][] text editor.
The module is distributed
under the `enum` name.


this repo | pypi
---- | ----
![latest tag](https://img.shields.io/github/tag/packagecontrol/enum34.svg) | [![pypi](https://img.shields.io/pypi/v/enum.svg)][pypi]


## How to use *enum* as a dependency

In order to tell Package Control
that you are using the *enum* module
in your ST package,
create a `dependencies.json` file
in your package root
with the following contents:

```js
{
   "*": {
      "*": [
         "enum"
      ]
   }
}
```

If the file exists already,
add `"enum"` to the every dependency list.

Then run the **Package Control: Satisfy Dependencies** command
to make Package Control
install the module for you locally
(if you don't have it already).

After all this
you can use `import enum`
in any of your Python plugins.

See also:
[Documentation on Dependencies](https://packagecontrol.io/docs/dependencies)


## How to update this repository (for contributors)

1. Download the latest tarball
   from [pypi][].
2. Delete everything inside the `all/` folder.
3. Copy the `enum/` folder (without docs)
   and everything related to copyright/licensing
   from the tarball
   to the `all/` folder.
4. Commit changes
   and either create a pull request
   or create a tag directly
   in the format `v<version>`
   (in case you have push access).


## License

The contents of the root folder
in this repository
are released
under the *public domain*.
The contents of the `all/` folder
fall under *their own bundled licenses*.


[enum34]: https://docs.python.org/3/library/enum.html
[Package Control]: http://packagecontrol.io/
[Sublime Text]: http://sublimetext.com/
[pypi]: https://pypi.python.org/pypi/enum34
