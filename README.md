# flymake-yamllint
A Flymake backend for validating YAML files for Emacs (26+), using
[yamllint](https://github.com/adrienverge/yamllint)

## Installation
`flymake-yamllint` is available on MELPA, so you can add it using your
preferred Emacs package manager or manually to your `load-path`.

## Usage
Make sure to have `yaml-mode` or similar installed before adding this
backend, and have it configured to open your YAML files if it doesn't
do that automatically.

Add the following to your `.emacs` file or other init file for Emacs
to load the backend when visiting a YAML file using `yaml-mode`.

```elisp
(add-hook 'yaml-mode-hook 'flymake-yamllint-setup)
```

Remember to enable `flymake-mode` as well, preferably after.

## License

Distributed under the GNU General Public License, version 3.
