# Pygments VIM Styles

A collection of famous VIM themes, fixed and converted to pygments CSS.
Feel free to fork and add your favorite theme using the guide below!

![Screenshot](https://github.com/uraimo/pygments-vimstyles/raw/master/screen.png)

Included vim color schemes:

**DARK BACKGROUND**

*Update 2015:*
- gruvbox (Thanks to [@daveyarwood](https://github.com/daveyarwood))

*Update 2014:*
- codeschool
- guardian
- twilight
- GRB256

*Update 2013:*

- desert
- mustang
- no_quarter
- peaksea
- railscasts
- rdark
- slate
- wombat
- freya   (Thanks to [@underhilllabs](https://github.com/underhilllabs))
- inkpot  (Thanks to [@underhilllabs](https://github.com/underhilllabs))


**LIGHT BACKGROUND**

*Update 2014:*
- github light

*Update 2013:*

- nuvola


### Convert your VIM styles
These CSS have been generated using the following script:

- https://github.com/honza/vim2pygments
- http://honza.ca/2011/02/how-to-convert-vim-colorschemes-to-pygments-themes

Troubleshooting:

Two possible issues you may encounter when converting your vim color scheme but that have an easy workaround:
- Launching pygmentize you could get a Python error related to a line that starts with a colon. Opening the .py you'll notice that the content of the line is duplicated by the previous one, simply delete the line starting with colon and relaunch pygmentize.
- Some vim schemes define color variables (it's vimscript afterall) and evaluate them using *exec '>color declaration>'* syntax, a dumb way to make the scheme digestible for vim2pygments is to manually replace the variables with their values and remove the *exec ''* calls. A bit of manual labour is involved but it works.

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
