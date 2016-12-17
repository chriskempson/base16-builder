# Base16 Update
This repository is deprecated as Base16 is changing the way it is built and maintained.

- More distributed, no longer has "one repository to rule them all!".
- Better structured for community involvement.  
- No longer tied to Ruby and has no official builder only implementations of builders that follow the (currently draft) spec found at at http://chriskempson.com/projects/base16.
- Scheme designers are no longer foced to have light and dark themes. You can now make a dark only or light only theme.
- Separated scheme files that now live in their creators repository.
- Separated template files that now live in their creators repository.
- Git used to pull in schemes/templates and keep them up-to-date.
- https://github.com/chriskempson/base16 to be repurposed to house discussion about base16 design away from code and syntax descriptions.
- Actually maintained!

## Why?
I made a mistake, this repository should only have containted the builder code, not the schemes nor the templates. Doing makes it very hard for others to implement a base16 builder in other languages. Furthermore, scheme and template creators should keep control of their work with their repositories becoming the official repositories issues and pull requests related to their work.

## How can I help?
If you have created a scheme or a template please become the owner of your work :smile: For scheme authors this means creating a repository for each of your schemes (see: https://github.com/chriskempson/base16-default-scheme as an example). For template authors this means creating a repository containing your template file converted to the new mustache format (see: https://github.com/chriskempson/base16-textmate as an example).

If you're skilled in any language and fancy maintaining a builder, see the spec at https://github.com/chriskempson/base16 and take a look at an example PHP implementation https://github.com/chriskempson/base16-builder-php.

## How can I build this new stuff?
Please see https://github.com/chriskempson/base16#builder-repositories for a list of builders in various languages.

## Questions?
Any questions can be raised as issues on https://github.com/chriskempson/base16

<hr />

# Base16 Builder
Easily build color variations of Base16 with YAML scheme definitions and ERB templates.
See the [Base16](https://github.com/chriskempson/base16) repository for more information.
Requires Ruby 1.9 or greater.

## Usage
    > ./base16
Build all schemes

    > ./base16 -s schemes/default.yml
Build only the "default" theme

    > ./base16 https://awesome-schemes.com/my-scheme.yml
Build a scheme stored on some webspace.

## Templates
* Ace
* Atom
* BBEdit (TextWrangler)
* Brackets
* Chrome DevTools (Web Inspector)
* Chrome Secure Shell
* CodeMirror
* ConEmu
* Console2
* Devtools-Author
* DrRacket
* Emacs
* Escape Code Shell Script (shell)
* Geany
* Gedit
* Gimp Palette
* Gnome Terminal
* Guake
* highlight.js
* Highlighting Kate
* HTML Preview (preview)
* IDEA
* IPython Notebook
* iTerm 2
* Konsole
* Mate Terminal
* MinTTY
* MultiMarkdown Composer 2 (mmdc2)
* Mou
* Notepad++
* OS X Terminal (terminal-app)
* Pantheon Terminal
* prettify.js
* Prism.js
* PuTTY
* Pygments
* Qt Creator
* Rainbow
* Rouge
* Sequel Pro
* Terminator
* Termite
* Textadept
* TextMate (Sublime Text)
* Vim
* Visual Studio
* Virtual Console (vconsole)
* Windows Command Prompt
* Xcode
* XFCE4 Terminal
* Xresources
* Zathura

## Maintainers
* [chriskempson](https://github.com/chriskempson) - HTML Preview, Vim, TextMate, iTerm 2, XFCE4 Terminal, Mou, Escape Code Shell Script, Gnome Terminal, BBEdit
* [jayferd](https://github.com/jayferd) - Rouge
* [neil477](https://github.com/neil477) - Emacs
* [joedynamite](https://github.com/joedynamite) - Xcode
* [robloach](https://github.com/robloach) - Geany
* [geoffstokes](https://github.com/geoffstokes) - Windows Command Prompt, MinTTY
* [idleberg](https://github.com/idleberg) - Ace, Atom, Brackets, Chrome DevTools, CodeMirror, Devtools-Author, Gedit, highlight.js, Notepad++, prettify.js, Pygments, Rainbow
* [rgieseke](https://github.com/rgieseke) - Textadept
* [oxplot](https://github.com/oxplot) - Mate Terminal
* [esn89](https://github.com/esn89) - Zathura PDF Reader
* [romainx](https://github.com/romainx) - MultiMarkdown Composer 2
* [moonpyk](https://github.com/moonpyk) - ConEmu
* [jprjr](https://github.com/jprjr) - ConnectBot, vx-connectbot
* [atelierbram](https://github.com/atelierbram) - Prism
* [bbrks](https://github.com/bbrks) - Sequel Pro

## License
Base16 Builder is released under the [MIT License](https://github.com/chriskempson/base16-builder/blob/master/LICENSE.md)
