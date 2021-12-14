# flymake-yamllint
A Flymake backend for validating YAML files for Emacs (26+), using [yamllint](https://github.com/adrienverge/yamllint)

## Installation
`flymake-yamllint` is available on MELPA so you can add it using your preferred Emacs package manager or manually to your `load-path`.

## Usage
Add the following to your `.emacs` files for Emacs to load the backend when visiting a YAML file

```elisp
(add-hook 'yaml-mode-hook 'flymake-yamllint-setup)
```

Remember to enable `flymake-mode` as well, preferably after.

## License

Distributed under the GNU General Public License, version 3.
