# planter-completion: zsh completions for Brett Terpstra's [Planter](http://brettterpstra.com/projects/planter/)

*planter-completion* picks up the viable names for Planter templates from your `~/.planter` directory and suggests them for auto-completion.  Ignores anything that isn't a `.tpl` file as specified in Brett's spec for the utility.

## Installing
Place `_planter-completion` somewhere that your zsh `fpath` will pick it up.

Also works perfectly fine as a custom [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) plugin.  Clone *planter-completion* in to the `~/.oh-my-zsh/custom/plugins` directory, then add `planter-completion` to the end of the `plugins` array in your `.zshrc` file.

## License

This is licensed under the WTFPL:

<pre>
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
</pre>
