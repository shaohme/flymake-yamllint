# flymake-yamllint
A Flymake backend for validating YAML files for Emacs (26+), using [yamllint](https://github.com/adrienverge/yamllint)

## Installation
For now `flymake-yamllint` is not on MELPA so you will have to add it to your `load-path` manually.

## Usage
Add the following to your `.emacs` files for Emacs to load the backend when visiting a YAML file

```elisp
(add-hook 'yaml-mode-hook 'flymake-yamllint-setup)
```

Remember to enable `flymake-mode` as well, preferably after.

## License

Distributed under the GNU General Public License, version 3.
