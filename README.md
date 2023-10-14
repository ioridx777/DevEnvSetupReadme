Personal Lunar vim setting
1. open ~/.config/lvim/config.lua
2. replace the file with your settings
3. restart lvim 

Setup Dev Environment for Chrome OS

Setup Nerd font 
1. <C-A-t> Open Crosh window
2. <C-J> Open developer console
3. Paste the following code and hit Enter
    term_.prefs_.set('font-family', 'JetBrains Mono Nerd Font, monospace');
    term_.prefs_.set('user-css-text', '@font-face {font-family: "JetBrains Mono Nerd Font"; src: url("https://raw.githubusercontent.com/ryanoasis/nerd-fonts/master/patched-fonts/JetBrainsMono/Ligatures/Regular/JetBrainsMonoNerdFont-Regular.ttf"); font-weight: normal; font-style: normal;} x-row {text-rendering: optimizeLegibility;font-variant-ligatures: normal;}')
4. Open terminal, go to terminal setting, the font should updated to JetBrainsMonoNerdFont-Regular
