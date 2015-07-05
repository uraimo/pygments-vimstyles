# Pygments VIM Styles

A collection of famous VIM theme, fixed and converted to pygments CSS.
Feel free to fork and add your favorite theme using the guide below!

Included until now:

[DARK BACKGROUND]

- desert
- mustang
- no_quarter
- peaksea
- railscasts
- rdark
- slate
- wombat
- freya   (Thanks to github.com/underhilllabs)
- inkpot  (Thanks to github.com/underhilllabs)

Update 2014:
- codeschool
- guardian
- twilight
- GRB256

Update 2015:
- gruvbox (Thanks to github.com/daveyarwood)

[LIGHT BACKGROUND]

- nuvola

Update 2014:
- github light

### Convert your VIM styles
These CSS have been generated using the following script:

- https://github.com/honza/vim2pygments
- http://honza.ca/2011/02/how-to-convert-vim-colorschemes-to-pygments-themes

Troubleshooting:

Two possible issue you could find while converting your vim color scheme that have an easy workaround:
- Launching pygmentize you get a python error related to a line that starts with a colon, opening the .py you'll notice the content of the line is duplicated by the previous one, simply delete the line starting with colon and relaunch pygmentize.
- Some vim schemes define color variables (it's vimscript afterall) and evaluate them using *exec '>color declaration>'* syntax, a dumb way to make the scheme digestible for vim2pygments is to manually replace the variable values and remove the *exec ''* calls.

### Themes
- Wombat: http://www.vim.org/scripts/script.php?script_id=1778

- Mustang: http://hcalves.deviantart.com/art/Mustang-Vim-Colorscheme-98974484

- Codeschool by AstonJ: http://astonj.com/tech/vim-for-ruby-rails-and-a-sexy-theme/ 
- Github by Anthony Carapetis: http://www.vim.org/scripts/script.php?script_id=2855

- Guardian by M. L. (anderskorte): http://www.vim.org/account/profile.php?user_id=6122

- Twilight by Henning Hasemann: http://leetless.de/

- GRB256 by Gary Bernhardt: http://destroyallsoftware.com/

- Gruvbox by Pavel Pertsev: https://github.com/morhetz/gruvbox

- Other VIM themes are part of the Color Sampler Pack http://www.vim.org/scripts/script.php?script_id=625 (originally from vim.sf.net )

### Example

![Screenshot](https://github.com/uraimo/pygments-vimstyles/raw/master/screen.png)
