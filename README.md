# PihkalaStyles
![lint status](https://github.com/Tutrox/PihkalaStyles/actions/workflows/lint.yml/badge.svg)

This repository is for the CSS used by [PihkalaTheme](https://github.com/Tutrox/PihkalaTheme).

## How is the code organized?

`pihkala.scss` is sorted like:

- First comes all of the variables

- Then we have all of the selectors that only extend selectors from Bootstrap

- Then we have the Bootstrap imports

- Between some imports we have some selectors with custom attributes (not in Bootstrap). They are placed after the import for the Bootstrap component it corresponds for.

> For example the `a` tags are styled in the `reboot` part of Bootstrap, so our custom `a` tag selector comes directly after the `reboot` import.
