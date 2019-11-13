# scopes-mode
Emacs major mode for the [Scopes](http://scopes.rocks/) programming language.
Highlights all keywords and numbers, along with all symbols defined in
`core.sc` and the default modules.

## Usage
The plugin is partially generated by a scopes program (`generator.sc`). To generate a new
version launch in a shell:

`scopes generator.sc > scopes-symbols.el`

The elisp library itself is already set up to use that file so no further
actions are needed. A pre generated version is already included in the
repository for convenience, so generation is only necessary if it's out of date.

## Screenshots
![light theme](https://cdn.discordapp.com/attachments/329404808643608586/644288603022819329/unknown.png)
![dark theme](https://cdn.discordapp.com/attachments/329404808643608586/644289540730912801/unknown.png)

## Special thanks

- [@flatwhatson](https://github.com/flatwhatson) for the help with the comment highlighting regex.
- [@hlissner](https://github.com/hlissner) for general emacs help; The indentation routine was also written
  while looking at the `pug-mode` package for reference.
