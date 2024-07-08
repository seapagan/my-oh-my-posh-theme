# My Custom `oh-my-posh` Theme

This is my custom theme for the [oh-my-posh](https://ohmyposh.dev/) prompt.
It is basically the `powerlevel10k_rainbow` theme with some minor changes,
including adding a transient prompt and changing slightly the Python venv
display.

I will be updating this theme as I see fit, feel free to use it as you see fit!

## How to use

To use this theme, you need to have `oh-my-posh` installed. You can install it
by following the instructions on the [official website](https://ohmyposh.dev/).

After installing `oh-my-posh`, you can use this theme by copying the content of
the `custom.toml` file into a folder dedicated for this, you can choose
whatever makes sense for you / your operating system. I use the 
`~/.config/ohmyposh/` folder for this on Linux, Mac or WSL.

Then, you can set the theme in your `~/.zshrc` file by adding the following 
line, changing the path to the `custom.toml` file if necessary. I add it at the
end of the file.:

```sh
# ~/.zshrc
# Set the theme using 'oh-my-posh'
eval "$(oh-my-posh init zsh --config ~/.config/ohmyposh/custom.toml)"
```

## License
Licensed under the MIT License, see the [LICENSE.txt](LICENSE.txt) file for 
information.

