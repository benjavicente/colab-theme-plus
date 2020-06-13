# Theme Spreadsheet

## Variables

### Colab variables

| Variable                          | Notes           |
| :-------------------------------- | :-------------- |
| `--colab-primary-surface-color`   |                 |
| `--colab-secondary-surface-color` | used for tables |
| `--colab-primary-text-color`      |                 |
| `--colab-toolbar-button-color`'   |                 |
| `--colab-border-color`            |                 |

### Custom variables

| Variable                   |
| :------------------------- |
| `--font-weight`            |
| `--code-cell-background`   |
| `--code-selected-active`   |
| `--code-selected-active`   |
| `--code-selected-inactive` |
| `--code-main`              |
| `--code-function`          |
| `--code-class`             |
| `--code-string`            |
| `--code-number`            |
| `--code-comment`           |
| `--code-punctuation`       |
| `--code-keywords-1`        |
| `--code-keywords-2`        |
| `--code-bool`              |
| `--code-arguments`         |

## Clases

### Dark theme clases

| Class  | Use                                             | Ex
| :----- | :---------------------------------------------- | -
| `mk1`  | main                                            |
| `mk4`  | function arguments                              |
| `mk5`  | strings, LaTeX `{}`                             | `'string'`
| `mk6`  | numbers                                         | `0`, `3.14`
| `mk8`  | comment                                         | `# comment`
| `mk9`  | boolean, reserved words, none                   | `True`, `False`, `None`, `def`
| `mk12` | punctuation                                     | `()`. `[]`, `{}`, `,`
| `mk14` | classes                                         |  `int`, `str`
| `mk15` | functions, methods                              | `zip`, `print`
| `mk18` | reserved words, commands, mk special characters | `in`, `not`, `%timeit`
| `mk19` | reserved words                                  | `for`, `import`, `return`

### Light theme clases

| Class  | Use                                                      | Ex
| :----- | :------------------------------------------------------- | -
| `mk1`  | main                                                     |
| `mk6`  | reserved words, commands, mk special characters, boolean | `in`, `not`, `def`, `%timeit`, `True`, `False`, `None`
| `mk8`  | comment                                                  | `# comment`
| `mk11` | numbers                                                  | `0`, `3.14`
| `mk13` | classes                                                  | `int`, `str`
| `mk14` | functions, methods                                       | `zip`, `print`
| `mk15` | function arguments                                       |
| `mk18` | reserved words                                           | `for`, `import`, `return`
| `mk26` | strings, LaTeX in Markdown                               | `'string'`