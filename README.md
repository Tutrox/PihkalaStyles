# PihkalaStyles
![lint status](https://github.com/Tutrox/PihkalaStyles/actions/workflows/lint.yml/badge.svg)

**ARCHIVED:** This project is not used anymore and is therefore archived since March 2022

---

This repository is for the CSS used by [PihkalaTheme](https://github.com/Tutrox/PihkalaTheme).

## How is the code organized?

The structure of `pihkala.scss` is the following:

- First comes all of the variables

- Then we have all of the selectors that only extend selectors from Bootstrap

- Then we have the Bootstrap imports

- Between some imports we have some selectors with custom attributes. They are placed after the import for the Bootstrap component it corresponds for --- for example the `a` tags are styled in the `reboot` part of Bootstrap, so our custom `a` tag selector comes directly after the `reboot` import
