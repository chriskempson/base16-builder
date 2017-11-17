# Base16 Update
This repository is **deprecated** as Base16 is changing the way it is built and maintained. No future PRs will be accepted.

- No longer tied to Ruby and has no official builder only implementations of builders that follow the (currently draft) spec found at at http://chriskempson.com/projects/base16.
- Scheme designers are no longer foced to have light and dark themes. You can now make a dark only or light only theme.
- Separated scheme files that now live in their creators repository.
- Separated template files that now live in their creators repository.
- Git used to pull in schemes/templates and keep them up-to-date.
- https://github.com/chriskempson/base16 to be repurposed to house discussion about base16 design away from code and syntax descriptions.

## Why?
I made a mistake, this repository should only have containted the builder code, not the schemes nor the templates. Doing makes it impossible to maintain. Furthermore, scheme and template creators should keep control of their work with their repositories becoming the official repositories issues and pull requests related to their work.

## How can I help?
If you have created a scheme or a template please become the owner of your work :smile: For scheme authors this means creating a repository for each of your schemes (see: https://github.com/chriskempson/base16-default-scheme as an example). For template authors this means creating a repository containing your template file converted to the new mustache format (see: https://github.com/chriskempson/base16-textmate as an example).

If you're skilled in any language and fancy maintaining a builder, see the spec at https://github.com/chriskempson/base16 and take a look at an example PHP implementation https://github.com/chriskempson/base16-builder-php.

## How can I build this new stuff?
Please see https://github.com/chriskempson/base16#builder-repositories for a list of builders in various languages.

## Questions?
Any questions can be raised as issues on https://github.com/chriskempson/base16
