# sublime-syntax-clingo
A syntax highlighting plugin for Answer Set Programming (ASP).

Previously I was using the "SWI-Prolog" syntax highlighting plugin for my ASP code. However, it does not support the ASP program with Python script in it, and it can't highlight ASP choice rules. I couldn't find a solution for it, so I wrote one. Feel free to use it, and let me know if you have any questions/bugs/suggestions.

### How to use
#### Automatic Installation
This package has been merged into the `Package Control` channel provided by `SublimeHQ`. I would highly recommend you to install from `Package Control`, so that you can get the latest updates automatically.

1. Goto `Package Control: Install Pacakge`.
2. Search for `Gringo`.
3. Hit the enter.
4. Done.


#### Manual Installation
1. Download the `gringo.sublime-syntax`, `gringo.tmPreferences` and `Gringo.sublime-build`.
2. Open your SublimeText, select `"Preference"->"Browse Packages..."`
3. Your file manager will open the `Package` for you.
4. Put the downloaded files under `User` folder.
5. Done.

### VIM User
I treat [SublimeText](http://www.sublimetext.com) as a GUI version of VIM. If you are a VIM user, you can visit [rkaminsk's repo](https://github.com/rkaminsk/vim-syntax-clingo) and get a plugin for vim.