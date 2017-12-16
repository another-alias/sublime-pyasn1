# *pyasn1* module for Package Control

This is the *[pyasn1][]* module bundled for usage with [Package Control][],
a package manager for the [Sublime Text][] text editor.


this repo | pypi
---- | ----
![latest tag](https://img.shields.io/github/tag/another-alias/sublime-pyasn1.svg) | [![pypi](https://img.shields.io/pypi/v/pyasn1.svg)][pypi]


## How to use *pyasn1* as a dependency

In order to tell Package Control
that you are using the *pyasn1* module
in your ST package,
create a `dependencies.json` file
in your package root
with the following contents:

```js
{
   "*": {
      "*": [
         "pyasn1"
      ]
   }
}
```

If the file exists already,
add `"pyasn1"` to the every dependency list.

Then run the **Package Control: Satisfy Dependencies** command
to make Package Control
install the module for you locally
(if you don't have it already).

After all this
you can use `import pyasn1`
in any of your Python plugins.

See also:
[Documentation on Dependencies](https://packagecontrol.io/docs/dependencies)


## How to update this repository (for contributors)

1. Download the latest tarball
   from [pypi][].
2. Delete everything inside the `all/` folder.
3. Copy the `pyasn1/` folder
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


[pyasn1]: http://snmplabs.com/pyasn1/
[Package Control]: http://packagecontrol.io/
[Sublime Text]: http://sublimetext.com/
[pypi]: https://pypi.python.org/pypi/pyasn1
